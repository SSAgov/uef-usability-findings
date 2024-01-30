# Round 5 UEF Pattern Usability Findings

Results overview from Round 5 of the user feedback sessions

## Background

The Mobile UEF team conducted usability testing to evaluate how a complex, linear application could be designed to work on mobile as well as desktop devices, using a responsive design approach. The existing MySSA application was modified to evaluate:

1. A proposed non-linear navigation structure; and
2. UEF patterns that might pose usability issues on smaller screens, thus needing further analysis or redesign.

The Mobile UEF team also sought to identify any emerging trends or patterns since beginning mobile usability testing last year. Patterns tested during this round included:

- Template Navigation
- State
- Definition Link
- Password (Create)
- Agreement Check Box
- Container with Tabs
- Address (International)
- Check List (Select All)
- Bank Information (International)
- Radio List (Other)

Testing was conducted on the following types of devices:

- Smartphones (iOS and Android)
- Tablet (Kindle Fire and iPad)
- Computers (Laptop - PC)

## The Prototype

The MySSA application used for testing was designed with a single breakpoint. When designing for breakpoints, we rely on the viewport size of the screen. It was decided by the Mobile UEF team that any device with a viewport size smaller than 768 received a smaller design specific for small screens. Similarly, any device with a viewport size larger than 768 received a larger design that represented the desktop screen design.

The devices with a viewport size of < 768 pixels included: the iPhone, Samsung Galaxy S3, and Kindle Fire HD (in portrait view).

The devices with a viewport size of 768 and larger included: Kindle Fire HD (in landscape view) and iPad. *(Note: participants using the Kindle device in this round of testing held it in portrait view only.)*

The viewport sizes for each mobile device are:

- iPhone 320 x 568
- Samsung Galaxy S3 360 x 640
- Kindle Fire 534 x 801
- iPad 768 x 1024

## What We Did

With members of the general public, Mobile UEF Team members:

- Conducted user testing with 31 participants at the Charles P. Miller Branch of the Howard County Public Library in Ellicott City, MD, on May 5th and 8th, 2014.
  - 31 participants tested on one of the following types of devices:
    - Mobile smartphone: 19 total participants (10 using an iPhone 5; 9 using a Samsung Galaxy S3)
    - Tablet: 10 participants (3 using a Kindle Fire HD; 7 using an iPad 3)
    - Desktop: 2 participants
- Collected participant information in a pre-test demographic survey, which showed:
  - One participant did not complete this survey, leaving 30 participants in total
  - Participants ranged in age from 22-77 with a median age of 49
  - 27 of the 30 participants owned and used at least one type of mobile device
  - Eight of the 30 participants had used Social Security’s online service to apply for, or to access, their benefits
  - Seven of the 30 participants stated they would use a tablet or smartphone to access SSA.gov or MySocialSecurity.
- Analyzed the results, including:
  - Navigation methods and preferences
  - Participant issues or comments re: specific UEF patterns or screen details
  - User satisfaction scores on the overall experience as indicated in a post-test questionnaire

## Challenges & Constraints

As with prior Mobile UEF testing sessions, recruiting of volunteer participants was performed on-site during the testing session with outreach to a broad range of library patrons. The usability test scenario and task were designed to be completed within 15-20 minutes, as prior mobile testing had shown this amount of time to yield the optimal balance of participants and data for analysis in any single testing day.

## Metrics

Metrics for this usability test were established by the UXG as follows:

- **Completion Rate** – Percentage of test participants who successfully complete the application without assistance
  - Target = 80% for each device type
- **Ease of Use** – Percentage of test participants who indicated the application was “very easy” to use on Questions #3, #5, and #8 of the post-test survey
  - Target = 80% for each device type
- **User Satisfaction** – Percentage of test participants who indicated they were “very satisfied” on questions #4 and #7 of the post-test survey
  - Target = 80% for each device type

## What We Learned

For each metric, actual performance exceeded the target for each device type.

| Metric  | Target (All)  | Actual (Phone)  | Actual (Tablet)  | Actual (Desktop)  |
|---|---|---|---|---|
| Completion Rate  | 80%  | 100%  | 100%  | 100%  |
| Ease of Use  | 80%  | 78%  | 80%  | 87%  |
| User Satisfaction  | 80%  | 81%  | 86%  | 100%  |

### Post-Test Questionnaire

The following table lists the Post-Test Questionnaire responses by device type as well as overall.

Scale of 1-5 where 1 = lowest and 5=highest

| Questions  | Smartphone (n=19)  | Tablet (n=10)  | Desktop (n=2)  | Overall  |
|---|---|---|---|---|
| How well did the website match your expectations?  | 4.07 | 3.88 | 4.5 | 3.98 |
| How well did the website support the task you were asked to perform?  | 4.13 | 4.25 | 5.0 | 4.15 |
| How difficult or easy was the website to use?  | 4.0 | 4.38 | 4.0 | 4.12 |
| Are you satisfied with the content?  | 4.13  | 4.38 | 5.0  | 4.19 |
| How difficult or easy was it to move through sections of the website? | 3.97 | 4.0 | 5.0 | 4.06 |
| How easy were the words on the website to understand?  | 4.17 | 4.38 | 4.0 | 4.25 |
| How satisfied are you with the speed at which you can complete tasks?  | 3.96 | 4.25 | 5.0 | 4.09 |
| How difficult or easy was it to find information you needed?  | 3.73 | 3.63 | 4.0 | 3.73 |
| How long would it take you to learn to use this website? | 4.18 | 4.25 | 5.0 | 4.18 |
| How confident did you feel using this application? | 4.29 | 4.63 | 5.0 | 4.36 |
| Average User Satisfaction Score by device type | 4.06 | 4.20 | 4.65 | - |

## Qualitative Assessment

Usability issues, as well as observations and participant comments, are listed below.

Small Breakpoint: Below 768 pixels (n=22)

Large Breakpoint: 768 pixels and above (n=9)

### NAVIGATION

#### **Menu**

Small Breakpoint

- 1 participant commented the menu was “very pretty.”
- Another found the menu color “too gray” and didn’t like it.
- 1 user suggested dimming the background when the menu appeared.
- 1 of the 7 participants that had no issues with the hamburger icon felt that the menu was “not a place to do things, just to get out.” This participant equated the hamburger with exiting but not with “bring a menu.”
- 5 participants did not expect to find the Sign Out in the Menu.
- 1 participant wanted the menu to drop down from the top instead of from the right.

![Closed Menu on Smartphone](/screenshots/round-5/01-menu-mobile-closed.png)

![Open Menu on Smartphone](/screenshots/round-5/01-menu-mobile-open.png)

Large Breakpoint

- 1 participant took “awhile” to find it and suggested “Maybe it should be over by Home.”

![Menu on Desktop](/screenshots/round-5/02-menu-desktop.png)

#### **Hamburger Icon**

- 7 of the 22 participants had no issues, quickly selecting this icon to see what options it presented; 1 of those stated it was “intuitive,” another stated it was “just like other sites,” and a 3rd stated it was easy.
- 1 participant who had difficulty finding the Sign Out under the hamburger icon commented that the icon is “ambiguous.”
- No specific comments on the large breakpoint.

![Hamburger Menu Icon](/screenshots/round-5/03-hamburger-icon.png)

#### **Sign Out**

- 2 participants were expecting to find Sign Out at the bottom, one saying “I don’t see a simple log out.”
- 1 participant said they would close the window by hitting the “x”, or by hitting the Home button.
- 1 participant did not expect Sign Out to be under a hamburger menu.
- 1 participant would “like to have a tab for log out.”
- No specific comments or issues on the large breakpoint.

### UEF PATTERNS

#### **State Field**

Small Breakpoint

- 2 participants weren’t clear that you must click “done” after selecting a state from the dropdown. (Note: this is an iOS issue.)
- 1 participant commented “It takes a little time to see where the state is.”
- 2 participants commented on wanting either the state or city to auto-populate, asking why you need to enter those if system has the zip code.

Large Breakpoint

- 1 participant said it would be nice for state to auto-populate after selecting zip.

![Address Pattern](/screenshots/round-5/04-address.png)

#### **Definition Link**

Small Breakpoint

- 4 participants did not know what the EIN was but did not click on the definition link.
- 2 participants did not know what EIN was and clicked on the definition link.
- 2 other participants wanted a “What’s this?” treatment or instructions. (Note: The definition link was changed to this treatment for Day 2 of testing and tested perfectly.)

Large Breakpoint

- 3 participants did not know what EIN was and wanted a “What’s this?” type of help.
- 1 participant clicked on the definition link and liked it.

![Definition using Help Link](/screenshots/round-5/05-definition-help-link.png)

#### **Password (Create)**

Small Breakpoint

- 3 participants indicated they liked the password indicator, with one commenting: “That’s nice. I like that it shows me that it matches” and another that she liked the criteria because it “tells her what is missing.”
- 2 participants were confused when re-entering password by the red incorrect message that appeared when they began typing.
- 2 participants voiced irritation at the complexity of the requirements.

Large Breakpoint

- 1 participant commented that password entry is “complicated, but it’s safe, so that’s ok.”
- Another commented that the password requirements were too complicated.
- A 3rd participant commented that password feedback was very nice, but that the rules were too ‘stringent’ and ‘might be hard to remember.”

![Password with No Text Entered](/screenshots/round-5/06-password-none.png)

![Password with Success and Errors](/screenshots/round-5/06-password-errors.png)

#### **Agreement Checkbox**

- No issues noted on either breakpoint.

![Agreement Checkbox](/screenshots/round-5/07-agreement.png)

#### **Container with Tabs**

Small Breakpoint

- 3 participants failed this task, due to problems with the pattern.
- 3 participants thought the tab arrow/icon was “confusing,” “not clear,” or “not very obvious.”
- 1 participant interpreted the tab icon to be a collapse/expand icon.
- 1 participant expected the dropdown to show more information.
- 1 participant clicked elsewhere first, then clicked icon, stating “It’s obvious once I focus on it.”
- Another participant had difficulty, stating when shown the icon, “I would never find that.”
- Yet another participant who had difficulty suggested “Instead of an arrow, how about ‘More….’”
- 1 participant had no problem with the icon.

![Container with Tabs on Mobile](/screenshots/round-5/08-container-tabs-mobile.png)

Large Breakpoint

- 1 participant shuffled through the tabs multiple times; they appeared to be trying to rectify multiple tab layers.
- Another participant immediately understood the tabs, while a 3rd took a while to find it.
- 1 participant did not think to scroll down because the containers fit the screen. They did not notice there was more.

![Container with Tabs on Desktop](/screenshots/round-5/08-container-tabs-desktop.png)

#### **International Address**

Small Breakpoint

- 1 participant did not select “international” for the phone number
- 1 participant noted the US was in alphabetical order vs. 1st on the list (Note: For Day 2 of testing, United States was moved to be the first entry on the list.)
- 2 participants commented that the country list is really long and requires a lot of scrolling.
- 1 participant asked why they couldn’t simply enter the first letter of the country and have the droplist go to that letter.

Large Breakpoint

- 1 participant wanted to put France in the State/Territory field and did not change the country to France.
- 1 participant wanted to “invoke the keyboard when choosing a country.”

![International Address United States Selected](/screenshots/round-5/09-intl-address-us.png)

![International Address France Selected](/screenshots/round-5/09-intl-address-france.png)

#### **Check List (Select All)**

- 1 participant volunteered that they “liked the check list.”
- Another participant suggested the maybe the “Select all” could be at the bottom.
- No issues noted on the large breakpoint.

![Checklist Select All](/screenshots/round-5/10-check-list-select-all.png)

#### **International Bank Information**

- 2 participants clicked the IBAN “? What’s this?” help link.
- 1 participant asked why the bank country list was so much shorter than the previous country list.
- 1 participant on the large breakpoint entered IBAN for the bank name.

![International Bank Information IBAN](/screenshots/round-5/11-intl-bank-info-iban.png)

![International Bank Information National Standard](/screenshots/round-5/11-intl-bank-info-standard.png)

![International Bank Information New Zealand](/screenshots/round-5/11-intl-bank-info-nz.png)

![International Bank Information Greece](/screenshots/round-5/11-intl-bank-info-gr.png)

#### **Radio List (Other)**

- 1 participant had difficulty with this pattern.
- 1 participant like the “quick options.”
- 3 participants wondered what date format they should be entering into the “Other” field; 1 of those suggested a calendar format would be helpful and another questioned why the “other field was unstructured.
- No issues noted on the large breakpoint.

![Radiolist with Other Option](/screenshots/round-5/12-radio-list-other.png)

### SCREEN DETAILS

#### **Placeholder Text**

- Two participants said it made no difference to them whether the placeholder text was an “x” or“#.”
- 2 other participants thought dashes were required.
- The 2 participants to voice an opinion preferred an “x” to a “#” symbol for a placeholder
- At least 2 participants expected the input to be formatted with dashes as the placeholder text had been.

![Phone Number with Placeholder Text as Numbers](/screenshots/round-5/13-phone-placeholder-numbers.png)

![Phone Number with Placeholder Text as a series of X characters](/screenshots/round-5/13-phone-placeholder-x.png)

#### **“Forgot?” Button**

Small Breakpoint

- 1 participant wondered whether the “Forgot?” referred to the Username or Password.
- 1 participant expects that the “Forgot” would ask for their username and would send an email to allow logging in – “everything should be in ‘Forgot.’”
- 1 participant expected that ‘Forgot?’ referred to both username and password and that either could be retrieved after answering some security questions [provided via ‘Forgot?’]

Large Breakpoint

- 1 participant expected to be able to reset her User ID, or password, or both.
- 1 participant thought perhaps ‘Forgot?’ would ask for their SSN to be entered and an email address.

![Sign In with Forgot Button](/screenshots/round-5/14-forgot-button.png)

#### **Creating an Account**

- 6 participants initially had difficulty creating an account and tried to do so in the Sign In area. Note: on smartphones the “Create Account” area was not visible without scrolling.
- No issues reported on large breakpoint.

![Sign In or Create an Account Screen](/screenshots/round-5/15-welcome.png)

## Next Steps

Based on this round of testing, the following patterns were found to be problematic for enough participants to necessitate a new or revised design:

- Hamburger icon representing menu
  - Both the icon (being unclear to a number of participants) and the functionality contained within it were unclear to a notable number of participants, as cited above.
- Container with Tabs
  - Both the container with tabs design tested on May 5th, and the alternate design tested on May 8th posed notable difficulty for participants, as cited above. Both designs are pictured, below:

Container with Tabs Day 1 Design:

![Container with Tabs on Day 1](/screenshots/round-5/16-tabs-mobile-day1.png)

Container with Tabs Day 2 Design:

![Container with Tabs on Day 2](/screenshots/round-5/16-tabs-mobile-day2.png)

### Additional Findings

- The placeholder text did not appear to add value. There was no significant preference for use of “x” as a placeholder, vs. “#.”
- The Definition Link pattern,  which led to significant difficulties on May 5th when displayed as a dotted underline, performed better on May 8th, when tested instead as a “?” followed by a “What’s This?” link.
- There may be value in creating two variations for the “Other” variations of the Check List and Radio List patterns: one for a text entry, and the other for a date entry.
- For the International Address pattern, there may be value in moving the United States selection from an alphabetical placement to placement as the first entry on the selection list.
- Treatment/placement of the Create an Account area may warrant further discussion regarding its placement in relation to the Sign In area.
