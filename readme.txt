=== Simple Tournament Brackets ===
Contributors: simpletournamentbrackets
Tags: tournament, bracket, bracket-generator, esports
Requires at least: 4.7
Tested up to: 6.4.3
Stable tag: 1.1.2
Requires PHP: 5.6.20
License: GPLv2
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Display simple tournament brackets on any page using a shortcode. Supports manual seeding and tournaments up to 256 competitors.

== Description ==

Use this plugin to create simple tournament brackets. It supports single elimination head-to-head tournaments in sizes of 4, 8, 16, 32, 64, 128, or 256 competitors. You can manually set the seeding when the tournament is started. Bracket colors can be modified in the WordPress backend -> Settings -> Tournaments page. 

You can display the brackets on any page using the `[simple-tournament-brackets tournament_id="$id"]` shortcode where **$id** corresponds to the *post_id* of the created tournament. The shortcode to use is also displayed for each tournament on the WordPress backend **All Tournaments** page.

Need support or have a feature request? Please reach out to us here on the WordPress.org forums or visit our website at [www.simpletournamentbrackets.com](https://www.simpletournamentbrackets.com).

== Frequently Asked Questions ==

= How do I change the colors used on the brackets? =

You can select the colors used on the brackets using the WordPress Backend -> Settings -> Tournaments page.

= I'm using the shortcode, but I don't see the brackets. How do I display the brackets after creating a tournament? =

After creating a tournament, you must click the **Start** action on the **All Tournaments** screen.

= How do I change the seeding of competitors on the bracket? =

Competitors are seeded in the order entered in the **Competitors** text area box displayed after clicking **Start**. You can randomize the seeding on the **Start** tournament screen by checking the checkbox, *Randomize Seeding*.

== Screenshots ==

1. A 16 competitor tournament. The cursor is hovering over Player7 and the brackets highlight Player7's path through the brackets. Use Simple Tournament Brackets plugin to run 4, 8, 16, 32, 64, 128, or 256 competitor tournaments.
2. Advance competitors through the brackets by viewing the brackets while authenticated as an admin. Hover the cursor over the gear icon to see the match dropdown menu. 
3. The WordPress backend **All Tournaments** list. You can find the shortcode for each tournament here as well as the **Start**, **Reset**, and **Finish** actions.
4. The WordPress backend **Start** tournament screen. Order competitors here to manually seed the tournament.
5. Easily modify the foreground and background colors for round headers, match, match hover, and the progress bar.

== Changelog ==

= 1.1.2 =
* Fixed: Matches do not advanced when seeded randomly.

= 1.1.1 =
* Fixed: Blank tournament brackets for new tournaments after 1.1.0 release.

= 1.1.0 =
* New: Added support for random bracket seeding.
* New: Added support for copying shortcode by clicking on the text in the tournament list.
* Changed: Improved the error message detail when attempting to start a tournament with invalid data.

= 1.0.1 =
* Fixed: Round headers appear as undefined when displaying more than one tournament on a single page with different number of rounds.

= 1.0 =
* The initial release.
