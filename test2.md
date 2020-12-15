# iPlayer Certification Product Test Charters - Playback

----------
## Functionality : VOD Playback 

### Feature : Playing VOD 
### Prerequisite :
A VOD programme is selected to play from Home Page and the dialog selections are already made 
### The Goal : VOD NFR-1 

| Goal |
| ----------- |
| Programme starts to play in 10 sec |


## Functionality : VOD ABR Switching

### Feature : ABR switching 
### Prerequisite : 
A VOD programme is selected to play from Home Page and the dialog selections are already made and is connected to a stable network 
### The Goal :  VOD ABR NFR-1  

| Goal |
| ----------- |
| It should not take more than 1 minute to switch to the highest quality stream. |

## Functionality: Parental Guidance

The Parental Guidance Lock helps you control what people in your household can and can't watch on iPlayer or listen to in BBC Sounds.

### Feature: Guidance and Parental Controls
### Pre-requisites: 
User has not set up the PG PIN on the application and selects a PG enabled VOD content to play.
### The Goal: GPC-1    

| Goal |Example|
| ----------- |-----------|
| Verify that upon choosing `I understand, continue`, you are taken to the Parental Controls dialog. |![Guidance](https://paper-attachments.dropbox.com/s_7E64603F9A1C51A7E0C390930FEEB8B52E3A1D28F375D1E027DBCDA211935FA8_1581086801613_Guidance.png)|


### Feature: Parental Guidance Lock set up
### Pre-requisites: 
User has not set up the PG PIN on the application; user has selected a PG enabled VOD content to play and choose `I understand, continue` on the Guidance dialog and next select the **Set up Parental Guidance lock** on the Parental Controls dialog. 

![Parental Controls](https://paper-attachments.dropbox.com/s_7E64603F9A1C51A7E0C390930FEEB8B52E3A1D28F375D1E027DBCDA211935FA8_1581093401035_Set+up+Parental+Controls.png)


### The Goal: PG-2, PG-3, PG-4, PG-6, PG-7, PG-8


| Goal |Example|
| ----------- |-----------|
| Verify that a PIN can be created following the parental guidance set up process. |![Create PIN](https://paper-attachments.dropbox.com/s_7E64603F9A1C51A7E0C390930FEEB8B52E3A1D28F375D1E027DBCDA211935FA8_1581096405499_PG+Set+Up+1.png)|
|Verify that a security question and answer set up can be done which is used to change the PIN.||
|Verify that after the parental guidance set up is completed, the selected VOD continue to play|![](https://paper-attachments.dropbox.com/s_7E64603F9A1C51A7E0C390930FEEB8B52E3A1D28F375D1E027DBCDA211935FA8_1581097080944_PG+Set+Up+8.png)|
|Select another PG enabled VOD content to play and verify that Parental Guidance Lock dialog is shown to enter the PIN.|![Create PIN](https://paper-attachments.dropbox.com/s_7E64603F9A1C51A7E0C390930FEEB8B52E3A1D28F375D1E027DBCDA211935FA8_1581096405499_PG+Set+Up+1.png)|
|Verify that after the PIN is entered and selecting OK, the VOD starts to play.|![](https://paper-attachments.dropbox.com/s_7E64603F9A1C51A7E0C390930FEEB8B52E3A1D28F375D1E027DBCDA211935FA8_1581338078529_PG+Lock+1.png)|
|Verify that it is not possible to proceed to the video if a wrong PIN has been entered.|| 


## Functionality: Playback Controls

Once a user has started to play a programme, playback controls (mini viewer) will be displayed at the bottom of the video. 

![Playback controls](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580309487476_Playback+Controls.png)


### Feature: Progress bar
### Pre-requisites: 
Select any VOD content item from Home section and the programme starts to play. 
### The Goal: CTRL-1, CTRL-2

| Goal |Example|
| ----------- |-----------|
|Verify that the mini viewer is displayed and the progress scrubber reflects the current video playback progress.|![Progress bar](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1581071096263_seek+bar.png)|
|CTRL-2 Verify that  time elapsed increments in line with playback progress and total duration is displayed as per the media asset.||
  
### Feature: Subtitles  
### Pre-requisites: Select a content item from Home that is not currently Live. Subtitles can be turned ON/ OFF  by toggling  the ‘S’ icon in the mini viewer. 
### The Goal: CTRL-3, CTRL-4     

| Goal | Example |
| ----------- | ----------- |
|Verify that the subtitles displayed are always in sync with the programme playing (with the provision that subtitles have been created correctly).|![Subtitles](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580486543874_subtitles.png)|
|Verify that after selecting to play another programme with subtitles, the programme played out is displayed with subtitles.||

## Functionality: Autoplay

When you get to the end of an episode, BBC iPlayer will automatically play the next episode. We call this Autoplay. 

### Feature: Next Episode autoplay
### Pre-requisites:  
Play an episode that has a next episode available, e.g., Series 1, Episode 1. 
### The Goal: AUTO-1

| Goal | Example |
| ----------- | ----------- |
|Verify that upon the countdown completion the next episode plays with no errors.|![Next Autoplay](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580308834398_Next_autoplay.png)|


### Feature: Windowed Credits
### Pre-requisites:  In an Autoplay journey, without a next episode, we'll recommend other content via a personal recommendations (P-Recs) feed. To get the p-rec autoplay, play the last episode of a programme and 
### The Goal: AUTO-4, AUTO-5

| Goal | Example |
| ----------- | ----------- |
|Verity that the entire video resizes in a smaller window in the left corner of the screen, whilst maintaining playback. ||
|Verify that resizing is smooth, audio is not interrupted, full screen image renders around the windowed playback with no issues.|![P-Recs Autoplay / Windowed Credits](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580307425625_p-recs+autoplay.png)|


## Functionality: Seeking 

### Feature: Live Seeking
### Pre-requisites: 
### The Goal: SEEK-1    

| Goal | Example |
| ----------- | ----------- |
|Verify that Selecting fast-forward and rewinding, the programme is paused and it begins to fast forward or rewind. The focus is on scrub bar slider, and selecting play or selecting up should return user to play state at normal speed.|![Live Seeking](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580490099833_Live+seeking.png)|


### Feature: Thumbnail seeking 
### Pre-requisites: Play any VOD content from the homepage
### The Goal: SEEK-2, SEEK-3

| Goal | Example |
| ----------- | ----------- |
|Verify  that thumbnails with a preview of the seeked to time are visible on screen. These consistently update to show the different part of the video.||
|Verify that throughout each increase in playback speed the thumbnails for the video are visible ||


Note: Depending on network speed there may be some black thumbnails at the highest speed but this should not entirely be the case. Thumbnail seeking not applicable to the Live, Audio Described, Signed and UHD content.

![Thumbnail seeking](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580484124550_seeking.png)

## Functionality: Live Simulcast

A live simulcast is what's being broadcast on a TV channel at that moment, or an event that's being broadcast at the same time that it's happening.  Live TV can be viewed through BBC iPlayer by going to Channels in the top navigation menu. Then select the On Now panel. 

![On Now panel](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580485789515_On+now.png)


### Feature:  On Now panel dialog
### Pre-requisites: Select content from the On Now Panel
### The Goal: LIVE-1, LIVE-2

| Goal | Example |
| ----------- | ----------- |
|Verify that pressing Watch from Start Button starts live playback from the beginning of the show. Verify no glimpse of Live Playback is seen |![Live Restart Choice Dialog](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580485814555_on+now+dialog.png)|
|Verify that pressing Watch Live Button starts live playback from the live of the show.||


### Feature: 2 hour window
### Pre-requisites: Go to Parliament/News/Alba channel and ensure that the current programme started over 2 hours ago.
### The Goal: LIVE-3

| Goal | Example |
| ----------- | ----------- |
|Verify that pressing "Watch from Start" on a programme started over 2 hours ago, takes the user to start of the window (Playback starts at x.x.x of time).|![2 hour window](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1580485975122_on+now+dialog+2h+window.png)|


### Feature: Play more content 
### Pre-requisites: Select content from the On Now Panel
### The Goal:  LIVE-4 , LIVE-5

| Goal | Example |
| ----------- | ----------- |
|Verify that LIVE playback after another LIVE playback Programme plays without any error. (Play a Live simulcast channel, stop it and then play another Live simulcast channel). ||
|Verify that VOD playback after LIVE playback plays without any error. (Play any content from the homepage that is not LIVE, stop it and then Live simulcast channel). ||


## Functionality : Live ABR Switching

### Feature : ABR switching 
### Prerequisite : 
A Live programme is selected to play from channels and the dialog selections are already made 
Device is connected to a stable network 
### The Goal : Live Playback-1, Live ABR NFR-1

| Goal | Example |
| ----------- | ----------- |
|Programme Starts to play ||
|It should not take more than 1 minute to switch to the highest quality stream.||

## Functionality: UHD  

### Feature: VOD UHD 
### Pre-requisites:  If a TV device is UHD compatible, it'll be possible to play all episodes of Dracula and Seven Worlds, One Planet on demand in Ultra HD (UHD).  Navigate to the Search page and play one of these programmes. 
### The Goal: UHD-1    

| Goal | Example |
| ----------- | ----------- |
|Verify that the playback controls show the UHD survey link and UHD labels|![VOD UHD](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1581077167004_UHD+VOD.png)|
|UHD-2 Verify that the video playback is smooth without any stuttering.||
|UHD-3 Verify iPlayer UI renders correct colours over UHD Playback |
![](https://paper-attachments.dropbox.com/s_3DDE3A8C2D1100D24AE8FD4870A31AA00584EFB79599DAB90FD867A08C10211C_1581588657025_iPlayer_UI_rendering_BT_2020_and_BT_709n_over_UHD_Playback_1.png)|


### Feature: Live UHD
### Pre-requisites:  Launch iPlayer in Beta mode and play the UHD beta trial video. 
(to play the trial vide navigate to Settings > Try new features in iPlayer BETA > Play UHD test loop)

![UHD trial video in Beta](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1581091763351_beta+mode.png)



### The Goal:  UHD-4, UHD-5
| Goal | Example |
| ----------- | ----------- |
|Verify that the playback controls show the UHD survey link and UHD labels. ||
|Verify that the UHD scream plays smooth without any stuttering. |![Live UHD controls](https://paper-attachments.dropbox.com/s_165B224F69ED0B510B002C0A9EB1624B03D9601D82F539D9CDCFDD5727FD73BF_1581091810287_live+uhd.png)|



