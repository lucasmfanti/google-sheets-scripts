# timestamp.gs
This is a script to try to have some structure and control when pulling data from a Google Sheets. With this script, we can check the first time a row was written, as well as the last update. We can also pull the user that performed the action. This script also includes the creation of an ID column to facilitate SQL joins downstream

# columns
In this example, the column A is the ID column, the E column is the user that created the entry on the database, and the F column is the timestamp to that entry (created_at). The G column is the editor of the last update, and the H column is the timestamp of the last update (updated_at). These columns can be changed easily on the script.