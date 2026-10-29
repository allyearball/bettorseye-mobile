# bettorseye: what to type into App Store Connect and Google Play

Everything here is written for the app as built: you sign in, and that's all. No prices, no plans,
no "subscribe" and no links out to sportsbooks. Don't add any of those words to the listing either.
Apple and Google read the listing as part of the app.

## Both stores

- **App name:** bettorseye
- **Subtitle (Apple, 30 characters max):** Player props, explained
- **Short description (Google, 80 characters max):** See how often a player prop hits and how each book prices it.
- **Category:** Sports
- **Support URL:** https://bettorseye.com
- **Privacy policy URL:** https://bettorseye.com/privacy
- **Marketing URL (optional):** https://bettorseye.com

**Full description:**

> bettorseye is a research tool for sports bettors who are 21 or older. For every player prop on
> tonight's NFL, NBA, MLB and WNBA games, it shows:
>
> - how often the player has gone over or under that line, in his last 10 games and this season
> - what our numbers say the chance is, next to the chance the sportsbook's price implies
> - the reasons behind each grade: minutes, matchup, injuries and who else is out
> - each book's price, side by side
>
> Save the bets you like, build a parlay and check how its legs move together, then see how your
> saved picks did.
>
> bettorseye doesn't take or place bets and isn't a sportsbook. Everything in the app is information
> only, with no guarantee of results. Sign in with your bettorseye account. New to bettorseye? Learn
> more at bettorseye.com.
>
> Gambling problem? Call 1-800-GAMBLER.

**Keywords (Apple, 100 characters max):** player props,sports betting,odds,NBA,NFL,MLB,WNBA,research,parlay,stats,picks

## Apple: App Review notes

> bettorseye is a free companion app to the paid web service at bettorseye.com (guideline 3.1.3(f)).
> The app only signs existing members in. You can't create an account, make a purchase, or see a
> price or a link to buy anything inside the app. Accounts are set up on our website.
>
> The app doesn't take, place or facilitate wagers, and doesn't link to any sportsbook. It shows
> statistics and publicly posted betting lines for research only. It's for adults 21+, and every
> page shows the 1-800-GAMBLER helpline.
>
> Demo account (Pro access):
> email: REVIEWER EMAIL HERE
> password: REVIEWER PASSWORD HERE

You make the demo account yourself on the admin page and give it Pro. Type the password only into
App Store Connect and Play Console, never into a file. Keep it working for as long as the app is in
review. Apple tests in the US, so it should open on a day with games.

**Age rating questionnaire:**
- Gambling: none. There's no real-money gambling in the app.
- Simulated gambling: none.
- Mature or suggestive themes: infrequent. That covers gambling references, i.e. betting lines.
- Set the age as **18+**.
- Everything else: none.

**App Privacy ("nutrition label"), data linked to the user:**
- Contact info: name, email address. Used for app functionality.
- Identifiers: user ID. Used for app functionality.
- Other data: date of birth (the 21+ check). Used for app functionality.
- Usage data: product interaction (which pages are opened). Used for analytics.
- Coarse location: the state, worked out from the connection, which decides which sportsbooks are
  shown. Used for app functionality.
- Tracking: **No**. Third-party advertising: **No**.

**Export compliance:** the app only uses standard HTTPS. This is already answered in the build
(ITSAppUsesNonExemptEncryption = NO).

**Screenshots:**
- Apple needs 6.9-inch iPhone screenshots, 1290 x 2796. An iPhone 16/17 Pro Max takes them natively.
  Otherwise Claude can render them from the live site.
- Take 3 to 5: Today, a bet page, Games, My bets.

## Google Play

- **App access:** "All or some functionality is restricted". Give the same demo account.
- **Ads:** No ads.
- **Content rating (IARC):**
  - Category: choose "Reference, News, or Educational".
  - Answer **Yes** to "references to gambling".
  - Answer **No** to real-money gambling and to simulated gambling.
- **Target audience:** 18 and over only.
- **Data safety:**
  - Same data as Apple's label: name, email, user IDs, date of birth, approximate location, app
    interactions.
  - All of it is encrypted in transit. Users can ask for it to be deleted (Account > Privacy > Delete
    my account).
  - Nothing is shared with third parties.
- **Gambling declaration (Policy > App content):** say the app has no real-money gambling. It's
  sports information only.
- **Closed testing first:**
  - New personal developer accounts must run a closed test with **at least 12 testers, opted in for
    14 days in a row**, before Google lets you apply for production.
  - Add 12+ Gmail addresses (friends or family) as testers on the closed track the day the first
    build is uploaded.
- **Graphics:**
  - 512 x 512 icon: `resources/icon-only.png`, resized.
  - 1024 x 500 feature graphic.
  - At least 2 phone screenshots.
