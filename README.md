Write-Host $NewGuests "new guest records found..."
$Report | Sort GroupName, Timestamp | Get-Unique -AsString | Format-Table Timestamp, Groupname, Guest

# An example script used to illustrate a concept. 

# Do not use my scripts in production until you are satisfied that the code meets the need of your organization. Never run any code downloaded from the Internet without
# first validating the code in a non-production environment.
