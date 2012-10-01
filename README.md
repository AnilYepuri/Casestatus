# A tiny USCIS case status scraper

## Background
I'm tired of refreshing the USCIS website to see how my
naturalization application is progressing, so I wrote this script to
check for me. 

## How To

Some details obfuscated.

```
$ ruby immicheck.rb "NBC*123456789"

{:status=>"Initial Review", :specific_info=>"On September xx, 20xx, we
mailed you an appointment notice to have your fingerprints taken. Please
follow the instructions on the notice. If you move while ...", 
:general_info=>"During this step, USCIS initiates the
background checks of the applicant/petitioner..."}
```
