# Discord: Definitive Edition
[A fanmade theme of a remaster for Discord].

To install and apply Definitive Edition, please get a modded version of Discord. (ex. Vencord, BetterDiscord etc)

# --INSTALLATION GUIDES--

APP: If you're using an app version of BetterDiscord or whatever, install the .css file on this page. Once that is done, open up Discord, click on settings and go to your themes section, click on "Upload Theme" or whatever it says for you. Alright, final step; just click on the .css file you installed from here, enable it and you should be good to go!

WEB: If you're using a Web extension for a modded Discord, there shouldn't be much of a difference. First up, install the .css file on this page. Once that is done, open up Discord, click on settings and go to your themes section, click on "Upload Theme" or whatever the button where you upload your theme says for you. Alright, final step; just click on the .css file you installed from here, enable it and you should be good to go!

NO INSTALLATION VERSION: From my awareness, this should work on BOTH app and web if I'm not mistaken. In this guide, as it says; you can get the theme without having to download ANYTHING from here, to do that please copy and paste the script below very carefully:

/**
 * @name Definitive Edition
 * @author lateyeezus
 * @version 1.0.0
 * @description Experience Discord the way it was truly meant to be created.
 * @source https://raw.githubusercontent.com/mwittrien/BetterDiscordAddons/master/Themes/BasicBackground/BasicBackground.theme.css
 * @website https://github.com/lateyeezus/Discord-Definitive-Edition
 * @authorId 1212629023361073182
 * @BDEditor BasicBackground
*/

@import url('https://fonts.googleapis.com/css2?family=PT+Sans:wght@100;300;400;500;700&display=swap');
@import url('https://mwittrien.github.io/BetterDiscordAddons/Themes/BasicBackground/BasicBackground.css');
@import url('https://mwittrien.github.io/BetterDiscordAddons/Themes/ServerColumns/ServerColumns.css');
@import url('https://discordstyles.github.io/RadialStatus/dist/RadialStatus.css');

:root {
  --background: url('https://i.imgur.com/VQJz00B.jpeg');
  --backgroundsize: cover;
  --backgroundposition: center;
  --backgroundblur: 0px;
  --popout: var(--background);
  --popoutsize: var(--backgroundsize);
  --backgroundposition: center;
  --popoutblur: 0px;
  --transparencycolor: 0,0,0;
  --accentcolor: 88,101,242;
  --backdrop: rgba(0,0,0,0.85);
  --textshadow: transparent;
  --transparencyalpha: 0.15;
  --messagetransparency: 0.1;
  --guildchanneltransparency: 0.15;
  --chatinputtransparency: 0;
  --memberlisttransparency: 0;
  --font: PT Sans;
  --textbrightest: 255,255,255;
  --textbrighter: 233,224,224;
  --textbright: 200,200,200;
  --textdark: 160,160,160;
  --textdarker: 125,125,125;
  --textdarkest: 87,87,87;
  --settingsicons: 1;
  --backdropsize: var(--background-size);
  --backdropblur: 0px;
  --version1_0_5: none;
  --columns: 3;
  --guildgap: 3;
  --aligndms: 0;
  --rs-small-spacing: 2px;
  --rs-medium-spacing: 2px;
  --rs-large-spacing: 2px;
  --rs-small-width: 2px;
  --rs-medium-width: 2px;
  --rs-large-width: 2px;
  --rs-avatar-shape: 50%;
  --rs-online-color: #D0FDE8;
  --rs-idle-color: #FFBF53;
  --rs-dnd-color: #FD8A8A;
  --rs-offline-color: #303133;
  --rs-streaming-color: #6441A4;
  --rs-phone-visible: none;
}

Once that has been copied, open Discord, head to Settings, go to your Themes section and you should see a button called "Edit QuickCSS". Click on it and something like a command prompt thingy should open but don't worry, keep it open and paste in what you just copied and your Theme should be good to go! If you'd like to remove it then just click on "Edit QuickCSS" and delete everything in there.
