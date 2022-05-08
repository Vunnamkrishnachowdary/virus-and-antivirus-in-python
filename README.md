<h1>Virus and Anti-virus detection:-</h1>
The virus program will be a program that would infect the victim file and copy its code into the file. This would create a self-replicating virus since the code keeps getting copied over and over. 
Antivirus Program:
The program has two ways of detecting the infected file - Simple signature detection & Variation in size difference. The hash signatures are downloaded and updated in the program and further the program has a list of functionalities such as - Scan, Quarantine, Full Scan etc. that the user can use in order to keep their device secure.
A single signature may be consistent with a large number of viruses. This allows the scanner to detect a brand-new virus it has never even seen before.
1. Replicating virus: A virus that infects and copies itself into every file of the folder it is run in. 
2. Simple Signature Detection: This is the module where we find out whether a file is infected by any known virus or not. 
3. Change in Size Detection: When the virus code copies itself into any file the size of the 
victim file increases. This is observed in this task. 
4. Update Hash Signature: We download known virus hash signature for the antivirus to identify it and take necessary action against it. 
5. Scan: Any file can be scanned to identify threats using this function. 
6. File Conversion to Hash: Shows no threat if no virus. Shows threat if virus present. 
7. Adding to Quarantine: Any suspected file can be added to the quarantine folder. 
8. Deleting files in Quarantine: We can delete the files in quarantine if proven necessary. 
9. Restoring files from Quarantine: We can restore any quarantined file if deemed not harmful or necessary.

<h2>Working of Computer Virus :</h2>
Computer viruses have a life cycle that starts when they're created and ends when they're 
completely eradicated. The following diagram points are describes in each stage.
Stage I - Creation – The Computer viruses are created by misguided individuals who wish to cause widespread, random damage to computers.
Stage II -Replication - Computer Viruses replicate by nature means it copies itself from one PC to anther PC.
Stage III -Activation - Viruses that have damage routines will activate when certain conditions are met. Viruses without damage routines don't activate, instead causing damage by stealing storage space.
Stage IV -Discovery - This phase doesn't always come after activation, but it usually does. Discovery normally takes place at least a year before the virus might have become a threat to the computing community.
Stages V -Assimilation - At this point, Antivirus developers modify their software so that it can detect the new virus. This can take anywhere from one day to six months, depending on the developer and the virus type.
Stage VI -Eradication - If enough users install up-to-date virus protection software, any virus can be wiped out. Viruses can not disappear completely, but some have long ceased to be a major threat.

<h2>Required imports :</h2>

Os,re,sys,glob,csv import tkinter, tkinter.scrolledtext
import threading
import os55⁵⁵import sys
import urllib.request
import glob
import time
import hashlib
import socket
import subprocess

Regular Expression, is a sequence of characters that forms a search pattern. RegEx can be used to check if a string contains the specified search pattern. It is used for scanning the victim file 

