# The *bbo_names.txt* file


When a player registers their details will appear in this on-line workbook [https://docs.google.com/spreadsheets/d/1DLdT67k0hdONGrm2uKFwJbjO8RcYBOj5Rj3SXpfior0/edit#gid=617644318](https://docs.google.com/spreadsheets/d/1DLdT67k0hdONGrm2uKFwJbjO8RcYBOj5Rj3SXpfior0/edit#gid=617644318).

![Player Workbook](/images/players_01.png)

1. Open the workbook given in the link above. Note that there are 6 columns. The left hand 4 columns are populated when the player submits their form (registers).

1. Sometimes the player enters spurious information in their BBO user name field. This will need to be removed manually.

1. We also require a first and last name; specifically there must be precisely one space in the name field.

1. If use the user does not have an EBU number, use the number 888888. This will ensure the file gets uploaded without EBU attempting to match the name to someone else's number.

1. The fifth column contains a formula that generates the players' details in a form that is required for EBU P2P uploads. To fill in this cell for a new user, copy and paste the formula from an existing player.

<a id="save_names_file"></a>

## Save names file to your PC

For scoring purposes you will need to save a copy of the names to your PC.

1. Highlight column E (headed *#names*) in the above work sheet;

1. copy the column using the mouse or *Ctrl+C*;

1. open a text editor (e.g. Notepad) on your PC and paste in the column using the mouse or *Ctrl+V* (Do not use Word or other wysiwyg editor.);

1. save the file as a text file to your *Downloads* directory, as it will be easier to locate when scoring (see <a href="scoring.html#scoring_update_scores">this section</a>). The file name doesn't matter a long as you remember it (e.g. bbo_names.txt). If you already have a file of that name there, you should over-write it.

## Robots

 If robots are playing in a tournament, the following entries need to be in  the *bbo_names* file:

    Robot,Advanced BBO, Bot A,900002
    Robot,Advanced BBO, Bot B,900003

 (see [this EBU forum entry](https://www.ebu.co.uk/forum/discussion/939/uploading-bbo-results-to-ebu-for-robot-players)).

