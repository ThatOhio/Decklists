# How-To
To track any deck, simply create a folder named after your deck with the following three text files (alternatively, copy the EmptyDeck folder and rename it): 
- Mainboard.txt
- Considering.txt
- Sideboard.txt

NOTE: Considering and Sideboard are only useful if you use those features in Moxfield. 

Once you have a folder with those text files, open your deck in Moxfield and click "Bulk Edit". Copy the values in the text boxes to their respective text document in your repo. 

Create a commit with the contents of your files. This will serve as a "starting point" for any future changes to the deck. 

Now you can go into moxfield and edit your deck freely. Adding and removing cards, moving them between considering / siderboard / mainboard, etc. 

Once you have made changes, simply repeat the process of clicking "Bulk Edit", this time replacing the contents of your text documents with the new contents containing your changes. 

Now when you make your commit with the updated text documents, git can provide you a simple Diff showing you what changes you've made, making it very simple to modify the deck in person.