Using rsync to avoid copying over unmodified files after the very first pack.sh command.

For unpack to work, drop the DataCenter files in this root folder.
Everything will be extracted in related language folder.

Then, execute ./copy.sh

It will copy over in the folder "datasheets" all the folders beside strSheets, so that we can have a global base to use for all DCs.

call unpack like so: ./unpack.sh
call pack like so: 
./pack.sh -a
./pack.sh EUR|GER|RUS|FRA
