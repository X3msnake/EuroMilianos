* Tradução Portuguesa via GPT-CHAT: **[> AQUI <](/README-PT.md) *** 

----

# EuroMilianos
### Simple random number generator for the european lottery euromilhões

![GPETAS - O Chico esperto de alfama](https://github.com/X3msnake/my-gists-files/blob/main/gpetas-euromillianos.gif)


#### THE STORY - GPETAS - O Chico-esperto de Alfama

This code was GPT-CHAT assisted, exercise in coding from my bro that knows very little about coding.

Initially he just asked GPT for a console generator, but since this was made for the use by a elderly person it was not ideal. 
After that, on my input he asked GPT to do it with a GUI (Graphic User Interface), the "AI" opted for tkinter (sensible choice since it comes preinstalled in python, no dependencies needed)
The new code ran but did not output anything or throw any errors.

On this report i asked bro to send me the code and i pasted GPT-CHAT his code back. 

It read it and told me what the code was for but, no mentioned of any issues.  
I requested it to explain why the code did not work, it was unable to, but did suggest printing statements on each segment of the code to see what was being fired and not. Even tho i pasted back to it the results it was still blind to the fault but by then i had an idea that the code was not running because Tkinter was not being fired somehow, so i google it and lo and behold "AI" had forgotten to initiate the tkinter window -> window.mainloop()

----

![GPETAS - O Chico esperto de alfama](https://github.com/X3msnake/my-gists-files/blob/main/gpt-chat-bs-itself-out-of-situation.png)

----

#### AFTER THE CHAT

So now we had a working MVP (Minimal Viable Product), but the used font and window was just too small. The best thing to do was to take the design in our controll with something preferably with a "What You See is What You Get" solution. That is Where [PAGE (Python Automatic GUI Generator)](https://sourceforge.net/projects/page/) comes in.

![GPETAS - O Chico esperto de alfama](https://github.com/X3msnake/my-gists-files/blob/main/gpt-on-PAGE.png)

The UI was built with PAGE and then I asked GPT to adapted it to go with the generated files from PAGE some extra elbow grease was needed to properly target the PAGE code script, namely how to properly target the lables, it was a matter of following the example that PAGE generates and adapting to it's naming conventions.
