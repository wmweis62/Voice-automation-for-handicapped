# Voice-automation-for-handicapped
I volunteer for Muscular Dystrophy Association and am donating my time to help people handicapped by the 43 diseases under the MDA Umbrella
I am new to this space and there is an immediate need to help a young man in my community achieve greater independence through voice 
activated solutions. The project I could use assistance with is helping him use voice commands to control his hospital bed. I purxchased 
an Amazon Echo for him and have been playing with some code from Kakopappa which has been a great introduction for me. I have a NodeMCU 
ESP8266 for my test lab. I need to control 4 relays, Raise Head, Lower Head, Raise Knees, Lower Knees. I am trying to consider all options.
I would prefer to drive some push solenoids to push buttons on a remote, but have not found the right components yet. If I interface into 
the bed itself, I have to make sure I do not cause damage to the bed by allowing the solution to drive the same bed part in two directions 
at once. My thoughts there would be to issue timed commands. Rather than say "Alexa, turn raise head" on followed by "Alexa, turn raise 
head off" (I would think latency would be an issue). Plus if the bed reaches full stop and has a active 'raise bed' command, and then a 
command is issued to lower the same bed parts, this could cause a problem.  

I would like to know how to take Kakopappa's code which turns on some relays to turning the relays on for a specified amount of time, like 
3-5 seconds. Also, I would like to see if there is an easy way to force all relays off before issuing each new command to prevent damage 
to the bed. 

Finally, the current commands in Alexa don't make sense for this application. "Alexa, turn raised head on" is clumsy. I would like to see
if we could educate Alexa to instead say "Alexa, raise head", "Alexa, lower head", "Aleza, raise knees", "Alexa, lower knees" This
May require AWS and Lambda which I know nothing about.
