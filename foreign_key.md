# Add Foreign Key


ALTER TABLE more_info ADD COLUMN character_id INT REFERENCES characters(character_id);