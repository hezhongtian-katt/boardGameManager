Ý PostgreSQL ½ßsq?[i@ psqlj?s?¢¶F
psql -U postgres -f create_board_game_db.sql
Á
\COPY board_game(id, name, type, description)
FROM 'C:\xxx\board_game_data.csv'
DELIMITER ',' CSV HEADER;
??
SELECT * FROM board_game;
