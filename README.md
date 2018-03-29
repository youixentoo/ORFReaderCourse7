# ORFReaderCourse7

Source needs Maven to run, otherwise just look in the pom.xml what to download and copy paste the source files to a project.
If you only want to see the program itself, download the .jar

# A tutorial to install Maven:
If you use Netbeans, <a href="https://youtu.be/3ODSQ0EpoQI?list=LLIf5VI5xhBnqfYTVi7Gz2cg">this</a> is all you need for instructions as Netbeans has a Maven plug-in standard.

# If you cannot BLAST:
- Open your cmd and see if you can use python there, use "python --version" or something like that.
- If that doesn't work, Python isn't (correctly) installed. 
Install Python 3.6 to fix it or if you already have Python 3.6 installed: In Windows you can manually add Python to your Path variables to fix it that way.

# Errors when running:
Errors get saved in a "ERRORS.txt" file in the working directory


# Design deviations
- een paar functies zijn niet beschreven in het ontwerp. Er is een mogelijkheid tot multiple fasta. Verder kunnen ook alle ORF's van het     genoom weergeven worden.
- De database connectie werkt niet. Deze kan niet verbinden met de cytosine server.
- De gebruikte MySQL connectie is versie 5 in plaats van versie 8.
- Het ERD is aangepast. De entiteit ORF heeft een primary key, namelijk orf_id.

<a href="https://github.com/youixentoo/ORFReaderCourse7OLD">For the old repo</a>
<br><br><br><br>Groepje: Thijs, Awan, Rivka
