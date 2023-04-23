READ ME - SLRO Report Filler
by StockhausenAmy

04/23/2023

This is a personal project I've been thinking about creating for a while. In my work at the Department of Natural Resources, our inspectors have to write
reports in response to every inspection they perform. This part of the process can take a while, and we've tried to identify tools that would speed it up.
One of the tools that has been used in the past is an Access database that allowed inspectors to fill out a form and generate a pre-filled report. The
problem with this is that no one has kept up the database, and we've been told by our IT Department that we will lose Access in the future, so we shouldn't
invest any further time in getting it running.

To me, the problem seems simple, but we don't have adequate tools to solve it. This is my attempt to fashion one of my own. This project should eventually
consist of a set of forms in which information about inspections can be entered and used to generate the script of a report. I cannot link this to a
database, like MySQL, because I work for a state agency, and they would balk at running any kind of homemade persistant database. Instead, this project
will read templates from Word docs, then fill in the appropriate information. Because it does not save or store anything, it should be permitted for use.
This configuration also makes it more user-friendly for others to update the templates in the future. No one will need to know the coding, and I can leave
instructions on where the files need to be located to work.

The SLRO Report Filler is currently in its very beginning stages. I intend to update this README as changes are made and features are added.
