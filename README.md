# ORFReaderCourse7

Source needs Maven to run, otherwise just look in the pom.xml what to download and copy paste the source files to a project.
If you only want to see the program itself, download the .zip

# A tutorial to install Maven:
If you use Netbeans, <a href="https://youtu.be/3ODSQ0EpoQI?list=LLIf5VI5xhBnqfYTVi7Gz2cg">this</a> is all you need for instructions as Netbeans has a Maven plug-in standard.

# If you cannot BLAST:
<ul>
  <li>Open your cmd and see if you can use python there, use "python --version" or something like that.</li>
  <li>If that doesn't work, Python isn't (correctly) installed.</li>
</ul>
Install Python 3.6 to fix it or if you already have Python 3.6 installed: In Windows you can manually add Python to your Path variables to fix it that way.

# Errors when running:
Errors get saved in a "ERRORS.txt" file in the working directory


# Design deviations:
A couple of functionalities in the application weren't described in the original design:
<ul>
  <li>The ability to read Fasta files with multiple headers</li>
  <li>All the ORFs that are found in the file get visualised</li>
  <li>There is a database created for the application, but due to problems with the server, there is no connection to it</li>
  <li>The used version of MySQL Connector/J is v5 instead of the described v8</li>
  <li>The ERD is modified so the entity "ORF" has a primary key "orf_id"</li>
</ul>
<br><br>
<a href="https://github.com/youixentoo/ORFReaderCourse7OLD">For the old repository</a>
<br><br><br><br>Group: Thijs, Awan, Rivka
