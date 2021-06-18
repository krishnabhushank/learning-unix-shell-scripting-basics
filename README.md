# Learn Unix Scripting Basics via Exercises

---

This project lists the various exercises that can be done to learn the scripting basics

---

[Exercise 1 : cp](#ex-1) : (script name : demoScript01.cp.sh)
- Create Script to Copy File from /tmp/file01.CpA to /tmp/file01.CpB
---
[Exercise 2 : cat](#ex-2) : (script names : demoScript02.cat.01.sh, demoScript02.cat.02.sh, demoScript02.cat.03.sh)
- Create Script to Display Contents of File /tmp/file02.CatA
- Create Script to Display Contents of Mutiple Files at Once /tmp/file02.CatA /tmp/file02.CatB
- Create Script to Concatenate Contents of Files /tmp/file02.CatA, /tmp/file02.CatB to /tmp/file02.CatC, and Display Contents of File
---
[Exercise 3 : echo and positional Parameters](#ex-3) : (script names : demoScript03.echo_posp.01.sh, demoScript03.echo_posp.02.sh, demoScript03.echo_posp.03.sh)
- Create script to read 3 inputs and display values of Inputs using echo
  ex. run the script as : sh script03.sh MyInputA MyInputB MyInputC
---
[Exercise 4 : If-then-fi and If-then-else-fi](#ex-4) : (script names : demoScript04.if_fi.01.sh, demoScript04.if_fi.02.sh)
- Create script to read 1 input and If the Input value is "NotGood", dsiplay "Problem, Input is NotGood"
- Create script to read 1 input and If the Input value is "NotGood", dsiplay "Problem, Input is NotGood". If Any other Input, dsiplay "Problem, Input is Other"
---
[Exercise 5 : Stream Redirection](#ex-5) : (script names : demoScript05.st_red.01.sh, demoScript05.st_red.02.sh)
- Create Script to Concatenate Contents of Files /tmp/file03.StreamRedA, /tmp/fileStreamRedB, and *Overwrite* to /tmp/fileStreamRedC
- Create Script to Concatenate Contents of Files /tmp/file03.StreamRedX, /tmp/fileStreamRedY, and *Append* to /tmp/fileStreamRedC
---
[Exercise 6 : touch, chmod (Permissions) & Exception Handling](#ex-6) :  (script names : demoScript06.touch_chmod_excph.01.sh)
- Create Script to
  - create dummy file /tmp/file04.EhB using touch
  - change permissions so that /tmp/file04.EhB is Readable but not writeable
  - copy data from /tmp/file04.EhB to /tmp/file04.EhB
  - capture the return code to li_rc 
  - based on value of li_rc display "copy failed" or "copy is a Success"
---
[Exercise 7 : Run Other Scripts from Your Script](#ex-7) :  (script names : demoScript07.run_other_scripts.01.sh, demoScript07.run_other_scripts.02.sh)
- Create Script to
  - call Script from this Exercise (#ex-1)
  - capture the return code
  - display the return code
- Create Script to
  - call Script from this Exercise (#ex-6)
  - capture the return code
  - display the return code