# scratch-usernames
A dataset of Scratch usernames and account IDs.

There is currently no publically available dataset (that I know of) that contains both usernames and their numerical account IDs. I decided to gather this data myself.

I did this through a Python script that requests the followers of accounts from the Scratch API. If new usernames are discovered, they are added to the all_users dictionary (the all_users.txt file in this repository) along with the associated ID. They are also added to the current unsearched list so that the script can later find the followers of them. I decided that this is an effective way to gather a large amount of usernames as followers are easy to find and easy to request data from. 

all_users.txt is formatted as a Python dictionary, unordered, with IDs as keys and usernames as values. It also happens to be in JSON format.
