# iPlayer Certification Product Test Charters - Home v1.1
----------

Instructions to use charters:

The iPlayer Product test pack is outlined in the mind map where the product main functionality and multiple features under a functionality are defined.

  

A brief explanation is given for each functionality to help for better understanding. A particular functionality may not consist of relevant charters but is limited to a context summary for your understanding .

  

Each charter includes four sections: Functionality, Feature, Pre-requisites and The Goal (there can be multiple goals per charter).

  

Functionality is a specific area of the product under TEST (e.g. Personalisation)

Feature is a particular product aspect of the area which is under TEST (e.g. Sign-in, Continue watching)

Pre-requisites are required mandatory actions to be fulfilled before the verification

The Goal is to verify the desired behaviour as mentioned, to observe and record the actual behaviour of the product aspect; this is also open for further exploration.

Each goal is identified by an identifier (e.g PER-2)


  

## Functionality: Homepage Personalisation

- As a signed in user, you will have a personalised experience. iPlayer will remember your preferences on all your other signed in devices.

- By ‘personalisation’ we mean:

- Remembering how far through a programme you are (so you can pick up where you left off) (Continue watching)

- Having the ability to add and remove your favourite programmes(Your added programmes)

- Content shown on home page is tailored to audience viewing habits. (Recommended for you)

- This functionality can be accessed through the Homepage.

- You can enable the feature Continue watching, if disabled by toggling on/off the personalisation from the settings menu within your account. Follow instructions in below screenshot.

  
  

![](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1568974865566_Screenshot+2019-09-20+at+11.18.45.png)

                                                      Highlight__blah__blah__blah

  
  

# Feature: “Continue Watching”

  

## Pre-requisites:

The user has signed in to the iPlayer app

## The Goal: PER-2

| Goal      | Example |
| ----------- | ----------- |
| Verify that a programme appears in “Continue Watching” after 30 secs of watching.      | ![](https://paper-attachments.dropbox.com/s_4CDF57DFFF10EB6469F22849E81D7484D7D54C0C9805F37343104E6A4073EB60_1606492646427_image.png)|


  

# Feature: “Your Added Programmes”

  

# Pre-requisites:

The user has signed in to the iPlayer app

# The Goal:

  

# PER-3

| Syntax      | Description |
| ----------- | ----------- |
| Verify that a programme can be added or removed from “Your added programmes” from the play-out page mini-viewer      | ![](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1566470768466_image.png)       |
| Paragraph   | Text        |


  

| - Verify that a programme can be added or removed from “Your added programmes” from the play-out page mini-viewer | ![](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1566470768466_image.png) |

| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |

| - Verify that a programme appears in the “Manage full list - Added programmes“ after selecting “Manage full list” from the home page | ![](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1566471082309_image.png) |

| - Verify that a programme can be removed from the “Your added programmes” after selecting “X” adjacent to the left of the programme in the “Manage full list - Added programmes“ page | ![](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1566470614287_image.png) |

| - Verify “Your added programmes” bundle disappears after all the added programmes are removed from the list | |

  

----------

# Functionality: Homepage Content items

  

All programmes on the home page are classified as “content items”.

  

- Content items can be:

- Episode content items - When in focus, the last row of the content item cycles between the following data:

- When it was First shown

- The duration

- The availability of the content.

  

Selecting the item will start the playback of the episode.

 |       |  | |
| ----------- | ----------- | ---- |
| ![Episode first shown](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1570018610078_image.png) | ![episode duration](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1570018481372_image.png) | ![episode availability](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1570018531612_image.png) |

- Top Level Editorial Object(TLEO) content items - TLEO content items are based on a programme. On selection of the item user will be taken to a ‘TLEO’ brand page which will surface all content items for that particular programme. On focus, there is no data about duration and availability.

  
  

![TLEO content item](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1568976596637_image.png)

  
  
  

# Feature: “Top Level Editorial Object(TLEO)”

  

## Pre-requisites:

The user has launched the iPlayer app, launch the TLEO (programme) page based on the description provided in the summary.

## The Goal:

  

CONT-1 Verify that the TLEO (programme) content page has an image in the top right; the title, genre, description and number of episodes should appear in the top left.

Verify that the TLEO content page has a list of series under the programme information if there is more than one series.

  

![](https://paper-attachments.dropbox.com/s_2A334D7AB84E86A54FE6454633BED3FAE9FB2E7DF2DCF09277F89DA23A01EC3F_1574418819344_Screenshot+2019-11-18+at+3.58.25+pm.png)

  

![](https://paper-attachments.dropbox.com/s_2A334D7AB84E86A54FE6454633BED3FAE9FB2E7DF2DCF09277F89DA23A01EC3F_1574420112592_Screenshot+2019-11-22+at+10.54.28+am.png)

  
  
  

----------

# Functionality: Homepage Bundles

  

Homepage consists of various bundles which may change based on editorial promotions. Bundles are located horizontally across the homepage and usually have a bundle title e.g. BBC Three, Most Popular.

  
  

![](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1569849161542_image.png)

  

![](https://paper-attachments.dropbox.com/s_ACE07469753DC2C988590B03970BF2D177010E2D3B8B8C9944C82DF73FC2DCBF_1569849187526_image.png)

  
  

There can be special editorial promotions on the homepage. These may be referred to as Live events bundle, Hero Promotion.

  
  

![Hero Promo](https://paper-attachments.dropbox.com/s_4CDF57DFFF10EB6469F22849E81D7484D7D54C0C9805F37343104E6A4073EB60_1606741526454_image.png)

![Live Event Bundle](https://paper-attachments.dropbox.com/s_4CDF57DFFF10EB6469F22849E81D7484D7D54C0C9805F37343104E6A4073EB60_1606741597628_image.png)

  

----------

# Functionality: Overflow Grids/View All

  

The “View All” buttons are journey links that appear at the end of bundles on the Home page, as shown below:

  

![](https://paper-attachments.dropbox.com/s_4CDF57DFFF10EB6469F22849E81D7484D7D54C0C9805F37343104E6A4073EB60_1606741756593_image.png)

   

There can be bundles present on the Home page which do not have a “View All” button


Content items may be truncated on to an overflow grid (max limit 80 but also de-duplicated where if there are multiple episodes from one TLEO, these will be combined into one programme item in the overflow grid)

  

# Feature: “Overflow/View All Journeys”

  

## Pre-requisites:

The user is currently on the Homepage

## The Goal:

  

OF-1 When a user selects the ‘View all’, they will be navigated to one of the following:-
 

![](https://paper-attachments.dropbox.com/s_99CB65C8F70024B615EEFDA74BF1B64506DFAAB0ABFD4E7A0D1492E2EEF76652_1570019213035_Screenshot+2019-10-02+at+1.26.09+pm.png)
 

1. An overflow grid page which will consist of content items related to the bundle selected
  

![](https://paper-attachments.dropbox.com/s_4CDF57DFFF10EB6469F22849E81D7484D7D54C0C9805F37343104E6A4073EB60_1606742056693_image.png)

 

2. A Categories page e.g. Categories>Drama


----------

Second Edit on the bottom
