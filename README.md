# qrq-fe
QRQ - A QR queuing system

Problem:
Waiting in lines all day long, no idea when they move, no idea until you go to a business if it's busy?

Solution:
A no nonsense system to solve wasting time waiting in lines. Improve communication, improve business, leads to happier customers.
All with a simple QR code

    Customer:
        - Seemless/frictionless signup 
        - Upfront information on where you are and how long you'll have to wait
        - Dynamic info (person per minute info) (average wait time) (early book/pause my spot?)

    Business:
        - Live feed of line status
        - Manage line dynamicly (VIP customers?)
        - Direct message / Group message
        - Control branding (colours, logo, messages)

FLOWS:

    New User (arrive at business `checkin-QR`):
    - Open camera app to look at QR code
    - User is directed to go to a special link
    - A page opens with information:
        - where they are
        - how many people are waiting
        - the next available slot (guess)
    - Q: Are they happy to join the line
    - IF they accept they are added to the line anonymously 
        - no details continue anonymously / website page will be updated until the spot is concluded or closed
        - they can also provide for quick sign in/recovery/future visits:
            - a phone number (asked if it is ok to be texted message updates, not required, remember me is also an option)
            - email address (asked if it is ok to be emailed message updates, not required, remember me is also an option)
            - social sign in e.g. google/apple/yahoo (asked if it is ok to be emailed message updates, not required, remember me is also an option)
        - they can also add extra info to help the business (at any time):
            - name (not required)
            - customer info / problem? (not required)
    
QR-CODES

    `check-in-QR` - The magic link to join the line advertised
    `check-out-QR` - The magic link to provide feedback/ free slot up (not always required)
    