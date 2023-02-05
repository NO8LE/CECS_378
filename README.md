# CECS_378
A semester-long project for CSULB's CECS 378 - Intro to Computer Security Principles

--------------------------------------------------------------------------------------
## WHAT?

	We plan to develop a WordPress vulnerability scanner and exploit tool.
--------------------------------------------------------------------------------------
## WHY?
	* Currently, ~42% of the internet's registered domains are hosted using wordpress sites.
	  That's millions upon millions of websites that are a target of our scanner.

	* There is a massive plugin and theme ecosystem that is often poorly maintained by individual
	  webmasters that leave us room for exploitation.

	* New CVEs / vulns are frequently reported and there are many public and private wp vulnerability
	  databases that have "researcher APIs" we can leverage.

	* Given everyone's skillsets and coding capabilities, the wp vuln scan/exploit tool is an
	  obtainable project for us to complete within a single semester.

	* the WordPress ecosystem is mature and we should be able to readily research and find
	  documentation as needed.
--------------------------------------------------------------------------------------
## HOW?
	We plan to write a tool that can identify and enumerate WordPress sites, then ID any vulnerable
	    plugins and themes by querying vulnDBs with free "researcher account level" API calls.
	
	We'll be using virtual private servers running Apache24 that host dummy sites with various
	    plugins and versions of WP.
	
	Additionally, we'll automatically attempt exploits which can be pulled from existing PoCs, CVEs,
	    Metasploit or Burp modules.
	
	Considering the small team, we can break up the development work across sprints and manage our
	    time through GitLab's built-in project-management tools like the KanBan board.
