# Nevron Office localization support
Nevron Office localization support
# Prerequisites
Nevron uses .TMX (Translation Memory eXchange) as the format for the localization dictionaries. The .TMX is an XML file and you can use a simple text editor, or an XML editor to contribute to the localization of the Nevron Office applicatons. You can also use the Nevron Dictionary editor free application to easily edit TMX localization dictionaries.

# Nevron Dictionary Editor
Currently the Dictionary Editor is available only for Windows. We will soon provide the Dictionary TMX Editor for Mac OSX.

You can find the Nevron Dictionary Editor in your distribution repository.

The main window of the application is divided into two areas - on the left one is shown a navigation tree view, which lets you select a category whose items to edit and on the right side is the table, which contains the keys and their translations for the selected category.

<b>User Interface</b>
The toolbar of the application contains the following buttons:
<ul>
  <li><b>Open</b> - lets you open a Nevron localization dictionary (in TMX format) for editing</li>
  <li><b>Import</b> - provides 2 useful functions:
  <ul>
    <li><b>Translations import</b> - lets you import dictionary translations from another dictionary. This is very useful when there's a new version of the localization dictionary, which contains additional texts to translate. You first have to open it with the <b>Open</b> button and then you can use the <b>Import</b> button to load your translations from an old dictionary and then overwrite the old dictionary using the <b>Save As</b> button.</li>
    <li><b>Dictionary data import</b> (for <a href="https://www.nevron.com/products-open-vision.aspx">NOV .NET Developers</a>) lets you import dictionary data from a Visual Studio Solution, C# Project File and C# Source Code File. This function scans the selected solution, project or file for localization calls like <b>NLoc.Get("my string")</b> or Nevron property names and adds them to the currently opened dictionary.</li>
   </ul>
  </li>
  <li><b>Save</b> - saves the changes to the currently opened dictionary</li>
  <li><b>Save As</b> - shows a Save File dialog for selecting where to save the current dictionary</li>
  <li><b>Not Translated</b> - when pressed, this toggle button hides all rows in the table, which have a translation. To show all rows again, simply click the button again to uncheck it.</li>
   </ul>
    <p>
        Next to the aforementioned buttons are the following widgets:
    </p>
    <ul>
        <li><b>Find text box</b> - finds all rows in the translation table of the currently selected category,
            which contain a word starting with the text entered in the text box. You can clear the filter either
            by deleting the text to find or by clicking the red 'X' button next to the find text box.
        </li>
        <li>
            <b>Culture combo box</b> - lets you select the culture, this dictionary provides translations for. For
            example: English (United States), Russian (Russia), Chinese etc.
        </li>
        <li><b>Help button</b> - shows this documentation.</li>
        <li><b>About button</b> - shows information about the application and its version.</li>
    </ul>

<b>Keyboard Support</b>

In case you want to copy all keys of the currently opened table to the clipboard so that you can then paste
        them in an Excel worksheet, a plain text file and so on, you should press "Ctrl + A" from the keyboard to select
        all rows and then "Ctrl + C" to copy the values in the "Key" column to the clipboard. You can also select only
        some of the rows by "Shift + Down Arrow" or "Ctrl + Left Click" on them.
