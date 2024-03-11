# ojsadmin
Secretary For Open Journal System

SPESIFICATIONS OF OJSADMIN SYSTEM

With OJSADMIN extension, some secretary workload is automated.
We generate Referee Acknowledgement Letters.
We generate Paper Acceptance Letters.
We show Referee Reports in a page, if you want you can download as pdf or print it out.
We show Referee Statistics in two pages: completed refereeings and ongoing ones. So, you can equally divide paper refereeing job with our system.

To handle all of above operations for your journal, there is a certificate settings page that must be fulfilled.
In order to compound a doi number, there must be given issue dates seperated by commas in the format (dd/mm,dd/mm,dd/mm,...).
Also start year of your journal is required for DOI number.
Head banner and signature as an image must be given.
The person's name holding the signature is required.
If you want to send your business card in outgoing emails, you must specify a business card as an image.
Journal Full Title and Short Name is taken from your database (do not worry, no data leakeage, only works in your server).
DOI number prefix is taken from your database.
The email that sends the letters is taken from your database but you must provide its password. In additon, you must provide SMTP adress and port number. Finally, mail server permissons must be given by hand.
There you are!

When you registered, you can access all of the specifications.
Data is taken from your database within your server, no data leakage.
Only two tables are inserted into your database in order to keep track of acknowledgement and acceptance letters.
The system works in OJS 3.x fluently. Also we have 2.8 version of the OJSADMIN system, please inquire.
In your server: Data retrieved internally from your server about papers, referees, statistics, referee reports. No data leakage.
In our server: In order to generate letters, only required info passed to our server (paper, paper number, referee name, doi number, your journal name, completed/applied dates, editor name and signature (as image, encryted when transferred)).
It is our duty to create pdf files according to data passed to our server, and send pdf file directly to your server. Your server sends emails on its own.
Everything is tested over 5 years through BMIJ and TUJOM journals in real databases.
If you encounter any problem, please let us know.

For subscription please visit www.ojsadmin.com
