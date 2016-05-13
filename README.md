# JSSUserComputerRename
Changes the OS X Computer Name to have a predetermined prefix followed by the JSS username of the user assigned to that device.


Copyright (c) 2016, JAMF Software, LLC.  All rights reserved.
       Redistribution and use in source and binary forms, with or without
       modification, are permitted provided that the following conditions are met:
               * Redistributions of source code must retain the above copyright
                 notice, this list of conditions and the following disclaimer.
               * Redistributions in binary form must reproduce the above copyright
                 notice, this list of conditions and the following disclaimer in the
                 documentation and/or other materials provided with the distribution.
               * Neither the name of the JAMF Software, LLC nor the
                 names of its contributors may be used to endorse or promote products
                 derived from this software without specific prior written permission.

       THIS SOFTWARE IS PROVIDED BY JAMF SOFTWARE, LLC "AS IS" AND ANY
       EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
       WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
       DISCLAIMED. IN NO EVENT SHALL JAMF SOFTWARE, LLC BE LIABLE FOR ANY
       DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
       (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
       LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
       ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
       (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
       SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

 
This script will rename the computer based on the user associated with it in the JSS
and is intended to be run as a policy or during imaging. You will need to set
parameters #4 & #5 as a JSS Username and the Password (respectively) with read access
to the computers object in the JSS.

Before running this script you will also need to set the JSS URL and a prefix (optional)
for the computer name with end result being PREFIX-USERNAME.

Written by: Joshua Roskos | Professional Services Engineer | JAMF Software

Created On: May 9th, 2016
Updated On: May 9th, 2016
