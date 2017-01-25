
This are checklists of tests (e.g. for alpha-testers) for given project (here for Galaxy42).

Files:
  * templ/ - template of the test (the emty checklist)
  * exec/ - dir with tests that were executed

How to run a test:
  * git clone this repository
  * create directory `exec/{yourname}/{gitrev}/` where gitrev is the git revision of software that you test
  * copy a templ/ file there as requested by project leaders
  * fill in the file there:
  * unroll loops by copy/pasting
  * fill in [...] with text e.g. with the loop "variables"
  * fill in [ ] with test result:  [+] test ok, [-] test failed, [?] not sure/misc
  * add details and commends
  * git commit this filled in file
  * make a PR to the main git repo

