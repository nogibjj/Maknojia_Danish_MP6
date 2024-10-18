```sql

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            
```

```response from databricks

[PARSE_SYNTAX_ERROR] Syntax error at or near '"PLAYER NAME"'. SQLSTATE: 42601 (line 4, pos 22)

== SQL ==

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
----------------------^^^
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            

```

```sql

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            
```

```response from databricks

[PARSE_SYNTAX_ERROR] Syntax error at or near '"PLAYER NAME"'. SQLSTATE: 42601 (line 4, pos 22)

== SQL ==

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
----------------------^^^
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            

```

```sql

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            
```

```response from databricks

[PARSE_SYNTAX_ERROR] Syntax error at or near '"PLAYER NAME"'. SQLSTATE: 42601 (line 4, pos 22)

== SQL ==

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
----------------------^^^
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            

```

```sql

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            
```

```response from databricks

[PARSE_SYNTAX_ERROR] Syntax error at or near '"PLAYER NAME"'. SQLSTATE: 42601 (line 4, pos 22)

== SQL ==

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
----------------------^^^
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            

```

```sql

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            
```

```response from databricks

[PARSE_SYNTAX_ERROR] Syntax error at or near '"PLAYER NAME"'. SQLSTATE: 42601 (line 4, pos 22)

== SQL ==

            WITH ranked_players AS (
                SELECT 
                    p."PLAYER NAME" AS player_name,
----------------------^^^
                    p."PROJ. FPTS" AS projected_points,
                    r.TEAM AS team,
                    r.OPP AS opponent,
                    r.MATCHUP AS matchup,
                    r."START/SIT" AS start_sit_status
                FROM WRRankingsWeek5PointsDB p
                JOIN WRRankingsWeek5RankingDB r
                ON p."PLAYER NAME" = r."PLAYER NAME"
            ),
            player_performance AS (
                SELECT 
                    player_name, 
                    team, 
                    opponent, 
                    projected_points, 
                    start_sit_status
                FROM ranked_players
                WHERE projected_points IS NOT NULL
                ORDER BY projected_points DESC
                LIMIT 10
            )
            SELECT * FROM player_performance;
            

```

```sql

    WITH ranked_players AS (
        SELECT 
            p.PLAYER_NAME AS player_name,
            p.PROJ_FPTS AS projected_points,
            r.TEAM AS team,
            r.OPP AS opponent,
            r.MATCHUP AS matchup,
            r.START_SIT AS start_sit_status
        FROM drm85_wr_points p
        JOIN drm85_wr_ranking r
        ON p.PLAYER_NAME = r.PLAYER_NAME
    ),
    player_performance AS (
        SELECT 
            player_name, 
            team, 
            opponent, 
            projected_points, 
            start_sit_status
        FROM ranked_players
        WHERE projected_points IS NOT NULL
        ORDER BY projected_points DESC
        LIMIT 10
    )
    SELECT * FROM player_performance;
    
```

```response from databricks
[TABLE_OR_VIEW_NOT_FOUND] The table or view `drm85_wr_points` cannot be found. Verify the spelling and correctness of the schema and catalog.
If you did not qualify the name with a schema, verify the current_schema() output, or qualify the name with the correct schema and catalog.
To tolerate the error on drop use DROP VIEW IF EXISTS or DROP TABLE IF EXISTS. SQLSTATE: 42P01; line 10 pos 13
```

```sql

    WITH ranked_players AS (
        SELECT 
            p.PLAYER_NAME AS player_name,
            p.PROJ_FPTS AS projected_points,
            r.TEAM AS team,
            r.OPP AS opponent,
            r.MATCHUP AS matchup,
            r.START_SIT AS start_sit_status
        FROM drm85_wr_points p
        JOIN drm85_wr_ranking r
        ON p.PLAYER_NAME = r.PLAYER_NAME
    ),
    player_performance AS (
        SELECT 
            player_name, 
            team, 
            opponent, 
            projected_points, 
            start_sit_status
        FROM ranked_players
        WHERE projected_points IS NOT NULL
        ORDER BY projected_points DESC
        LIMIT 10
    )
    SELECT * FROM player_performance;
    
```

```response from databricks
[TABLE_OR_VIEW_NOT_FOUND] The table or view `drm85_wr_points` cannot be found. Verify the spelling and correctness of the schema and catalog.
If you did not qualify the name with a schema, verify the current_schema() output, or qualify the name with the correct schema and catalog.
To tolerate the error on drop use DROP VIEW IF EXISTS or DROP TABLE IF EXISTS. SQLSTATE: 42P01; line 10 pos 13
```

```sql

    WITH ranked_players AS (
        SELECT 
            p.PLAYER_NAME AS player_name,
            p.PROJ_FPTS AS projected_points,
            r.TEAM AS team,
            r.OPP AS opponent,
            r.MATCHUP AS matchup,
            r.START_SIT AS start_sit_status
        FROM drm85_wr_points p
        JOIN drm85_wr_ranking r
        ON p.PLAYER_NAME = r.PLAYER_NAME
    ),
    player_performance AS (
        SELECT 
            player_name, 
            team, 
            opponent, 
            projected_points, 
            start_sit_status
        FROM ranked_players
        WHERE projected_points IS NOT NULL
        ORDER BY projected_points DESC
        LIMIT 10
    )
    SELECT * FROM player_performance;
    
```

```response from databricks
[TABLE_OR_VIEW_NOT_FOUND] The table or view `drm85_wr_points` cannot be found. Verify the spelling and correctness of the schema and catalog.
If you did not qualify the name with a schema, verify the current_schema() output, or qualify the name with the correct schema and catalog.
To tolerate the error on drop use DROP VIEW IF EXISTS or DROP TABLE IF EXISTS. SQLSTATE: 42P01; line 10 pos 13
```

