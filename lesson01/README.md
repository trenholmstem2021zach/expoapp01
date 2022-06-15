# Build Demo Phone App Lesson

## NOTE: Make sure you have [installed the DevTools](https://github.com/trenholmstem2021zach/expoapp01#setup-development-tools) 

## Step #1: Start NGrok RevProxy for Expo Phone App

### Open a new Windows Console
type ngrok http 19000:
<code>
ngrok http 19000

NOTE: You should see:
Session Status  online                                                                                            
Account         trenholmstem2021zach (Plan: Free)                                                                 
Update          update available (version 3.0.4, Ctrl-U to update)                                                
Version         3.0.2                                                                                             
Region          United States (us)                                                                                
Latency         calculating...                                                                                    
Web Interface   http://127.0.0.1:4040                                                                             
Forwarding      https://f150-97-82-25-49.ngrok.io -> http://localhost:19000                                    
                                                                                                                                
Connections   ttl     opn     rt1     rt5     p50     p90                                                       
              0       0       0.00    0.00    0.00    0.00      

</code>

## Step #2: Create Demo Tab Phone App.

Open a Windows Console:

NOTE: After the init you will use the arrow keys to select tabs template See below

Session Status  online                                                                                            
Account         trenholmstem2021zach (Plan: Free)                                                                 
Update          update available (version 3.0.4, Ctrl-U to update)                                                
Version         3.0.2                                                                                             
Region          United States (us)                                                                                
Latency         calculating...                                                                                    
Web Interface   http://127.0.0.1:4040                                                                             
Forwarding      https://f150-97-82-25-49.ngrok.io -> http://localhost:19000                                    
                                                                                                                                
Connections                   ttl     opn     rt1     rt5     p50     p90                                                       
                              0       0       0.00    0.00    0.00    0.00                   

## Step #2:  Start Demo app

### Open a new Windows Console

Type first: expo init
<code> 
expo init
> ? What would you like to name your app? › my-app



? Choose a template: › - Use arrow-keys. Return to submit.
    ----- Managed workflow -----
    blank               a minimal app as clean as an empty canvas
    blank (TypeScript)  same as blank but with TypeScript configuration
❯   tabs (TypeScript)   several example screens and tabs using react-navigation and TypeScript
    ----- Bare workflow -----
    minimal             bare and minimal, just the essentials to get you started
✔ Downloaded template.
🧶 Using Yarn to install packages. Pass --npm to use npm instead.
⠼ Installing JavaScript

...
✔ Installed JavaScript dependencies.

✅ Your project is ready!

To run your project, navigate to the directory and run one of the following yarn commands.

- cd my-app
- yarn start # you can open iOS, Android, or web from here, or run them directly with the commands below.
- yarn android
- yarn ios
- yarn web
Project is already inside of a git repo, skipping git init.
</code>

## Step #3: Next Let's test on our Phone

In your Windows console change directory to my-app

<code>
cd my-app
yarn start
› Metro waiting on exp://192.168.1.7:19000
› Scan the QR code above with Expo Go (Android) or the Camera app (iOS)

› Press a │ open Android
› Press i │ open iOS simulator
› Press w │ open web

› Press r │ reload app
› Press m │ toggle menu
› Press d │ show developer tools
› shift+d │ toggle auto opening developer tools on startup (disabled)

› Press ? │ show all commands

Logs for your project will appear below. Press Ctrl+C to exit.
Started Metro Bundler

</code>

NOTE: The above output should be displayed.

## Step #4:  Enable Tunnel for Expo App

### In same expo Console Window.

Click type 'd' to enter developer mode.

NOTE: A browser will open and you should see on the left side some settings.   Select tunnel on the button selectors where it says tunnel - LAN - Local.

Copy the new URL which will look something like:  exp://sy-kky.anonymous.my-app.exp.direct:80 and send or message to your phone using whatsapp, text or manully email or facebook messenger.

## Step #5: View App on your Phone

### NOTE: Your link will be different.
On your phone click on link: exp://sy-kky.anonymous.my-app.exp.direct:80
