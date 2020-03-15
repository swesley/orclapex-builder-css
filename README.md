# orclapex-builder-css
The application builder introduced in APEX 5.x is fantastic, but I found it a little washed out. I restored some of the 4.x colours to help distinguish page regions, plus a few other tweaks, such as moving the success message so it no longer covers key buttons.

![alt text](https://github.com/swesley/orclapex-builder-css/raw/master/apex-contrast-example.png "Example contrast differences")

Detail for use described on this [blog post](http://www.grassroots-oracle.com/2015/08/apex-5-colour-contrast.html). I use a browser extension to apply the attached CSS to selected websites (where APEX lives).

## Usage
1) Install an browser extension such as Stylebot. Adblockers often has a place for site-specific CSS
2) Define a style for the URL your APEX is located, eg: apex.oracle.com
3) Paste the relevant CSS for your preferred mode.

There appears to be no class differences between the light & dark modes, so you won't be able to flip between the two modes without changing your integrated CSS.

## light-mode-ocean
Built for 5.x, it has actioned my intention since, inhereting the blue styling from 4.1.
While I was creating dark mode CSS, I noticed a few of the selectors were no longer relevant for 18.1.

## light-mode-earth
A green motif returned with the arrival of 20.1, I split the light-mode files according to the general colour scheme. This now works better in dark mode, since you can't automatically switch this CSS when switching between modes.

## dark-mode
I've started a new stylesheet for Dark Mode in APEX 19.x. Some of the selectors I've used previously are no longer relevant, so I've only inlcuded those selectors I still appreciate.
It has been [suggested](https://twitter.com/mikehichwa1/status/1173803917664108544) the contrast may be addressed in 20.1 (it has).

## Some CSS Results
- Strengthen region headers, to add contrast between sections, helping your eyes to skim vertically
- Move success message from RHS to LHS, to stop it covering that key control panel
- Widen scrollbars
- Increased font size for Shared Component menu
- Increased search box size
