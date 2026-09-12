Wireframe Archive
+++++++++++++++++

This is a public mirror to collection of wireframes for my submission of Web Development to University
of London. Please note that each file has a specific meaning:

e.g. Lindexm.dot means a low fidelity index page wireframe for mobile phone.

Please build all these by issuing the following command to your terminal:

----> for f in *.dot; do
---->  dot -Tpng "$f" -o "${f%.dot}.png"
----> done
