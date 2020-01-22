2020-01-22, Version 4.2.0
=========================

 * chore: rebrand for publish (Kevin Delisle)

 * Remove profanity. (Matt R. Wilson)

 * Update FUNDING.yml (Marak)

 * Create Funding.yml (Marak)

 * test: check generated ethereum addresses are all lowercase (A.J. May)

 * fix: lowercase eth addresses (A.J. May)

 * [dist] [fix] [minor] Demo page (Marak)

 * docs(README): fix typo (Erwann Mest)

 * Fix file encoding issue in Farsi locale (Deniz Dogan)

 * [api] Added vehicle module #555 (Marak)

 * [api] [refactor] Remove `bindAll` method #376   * Was previously used for `this` scoping issue   * Should no longer be needed   * Should not cause any issues (Marak)

 * [api] [minor] Remove reference to `this` (Marak)

 * [test] [minor] Improving test coverage (Marak)

 * [api] [fix] [minor] Remove `this` scope #376 (Marak)

 * [test] Add `faker.fake` functional tests #386   - Now running all methods through faker.fake   - Adds coverage for scope issues #376   - Refactors functional test methods to helper (Marak)

 * [api] [minor] Remove `this` reference #718 #376 (Marak)

 * resolve conflict (Tyler)

 * merge with master (Tyler)

 * [test] `faker.fake` now at 100% code coverage (Marak)

 * [api] `faker.fake` should throw error on empty   * Was previously returning error as string   * Throwing errors conforms to existing APIs (Marak)

 * [vendor] [minor] Removing dead code (Marak)

 * [test] Increasing coverage for Mersenne Twister   * Covers internal argument validation   * This validation is already tested upstream (Marak)

 * [dist] [minor] Add reports folder to .gitignore (Marak)

 * Improve unit tests for name.findName() and name.prefix() (Tito Nobre)

 * Improve pt_PT name prefixes (Tito Nobre)

 * Improve locale pt_PT with city names (Tito Nobre)

 * Improve locale pt_PT with cell_phone formats (Tito Nobre)

 * Update pt_PT references (Tito Nobre)

 * Add locale pt_PT (Tito Nobre)

 * [fix] Mersenne Twister seed_array #712 (Marak)

 * [fix] Code styling for undefined check #711 (Marak)

 * style(date): Avoid use of ternary expressions for optional args (Droogans)

 * fix(date): Allow for `refDate` in `soon()`, `recent()` (Droogans)

 * Improve Canadian local postal code support (Gerson Niño)

 * Added and corrected (Utsav Bhardwaj)

 * Updated and ordered (Utsav Bhardwaj)

 * [minor] Spelling error in tests (Marak)

 * Add tests (Mahmoud Gamal)

 * Support variable precision for latitude and longitude (Mahmoud Gamal)

 * fix(bitcoinAddress): fix tests for bitcoin addresses (Ash Prosser)

 * added south african names and details (Paul Salmon)

 * Add mixed options shape to the documentation (Tomassito)

 * [dist] Added `CODE_OF_MERIT` (Marak)

 * [api] [fix] [refactor] Unique options into class   * #466 #596   * Fixes scope issues with max values (Marak)

 * [fix] Copy paste error in `ar` local #505 (Marak)

 * fix: system.directoryPath and system.filePath (Simone Sanfratello)

 * Update last_name.js (David Fernández)

 * Update adjective.js (David Fernández)

 * [dist] [minor] Update code highlighting in docs (Marak)

 * change shas to use hex chars (Danielle Adams)

 * add commit entry and remove readme changes (Danielle Adams)

 * cleanup tests and formatting (Danielle Adams)

 * add git to readme (Danielle Adams)

 * add git module to lib (Danielle Adams)

 * add unit test for git module (Danielle Adams)

 * [dist] Update demo page to jQuery v3.3.1 #489 (Marak)

 * [api] [fix] user-agent randomness #521   * Now using `faker.random.number`   * Adds faker seed and mersenne (Marak)

 * [minor] [fix] Missing comma #397 (Marak)

 * Added some names (Per Ström)

 * Added `ar` locale (partial ) #505   * Merges work from @atefBB   * Original PR could not be merged (Marak)

 * [api] [minor] Don’t use `Object.assign`   * Should fix tests for `faker.random.float`   * Was causing older versions of Node to fail (Marak)

 * [api] Add method `faker.random.float` - Extends the `faker.random.number` float to automatically return a 0.01 precision float - First parameter is set as the precision value (Jimmy Cann)

 * Added more node versions to travis-ci (Kevin Yue)

 * Added custom background color to data URI image (Kevin Yue)

 * Make data URI text align center and middle (Kevin Yue)

 * feat: add "blockchains" as a company.bs_noun (Sean)

 * - registering new locale (fr-ch) (Jérome Freyre)

 * Update formats.js (Paweł Kuna)

 * Fix docJS for faker.phone namespace (Arseniy Pavlenko)

 * Remove controversial name from source (Bas Huis)

 * Update prefix.js (sbmart)

 * Update product_name.js (sbmart)

 * Update department.js (sbmart)

 * Update noun.js (sbmart)

 * Update ingverb.js (sbmart)

 * Update abbreviation.js (sbmart)

 * Update verb.js (sbmart)

 * Various fixes (David Fernández)

 * Missing accents (David Fernández)

 * Fix bitcoinAddress generator (John Maia)

 * refactors zipCodeByState to match correct zip code ranges with tests (Willy Raedy)

 * Adding test for zipcode by state, basic functionality (Karl Hughes)

 * Reset startTime appropriately (Rich Churcher)

 * Add commerce locale ES (ru03)

 * Update male_first_name.js (bakwan)

 * don't npmignore build/build/faker.js and build/build/faker.min.js even though we ignore the rest of build/* (Casey Watts)

 * Doc for replaceSymbols extended (Iaroslav Popov)

 * add direction abbr options with tests (Tyler)

 * add missing colon (Tyler)

 * add direction generator and test (Tyler)

 * add unit tests and schema desciptions (Tyler)

 * add ordinal and cardinal direction generator to address namespace (Tyler)

 * re-order of the company.bs adjective and buzz (#496) (mbehzad)

 * Update docs.md (Daniel Biedma)

 * add missing semicolons (Tyler)

 * remove hardcoded vin numbers array (Tyler)

 * update vin to return randomly generated vin and update tests (Tyler)

 * add random.alpaha with tests (Tyler)

 * fix typo in lib/vehicle.js comment (Tyler Reichle)

 * add missing semicolon to en/index.js (Tyler Reichle)

 * Remove the number 2008 from pl/address/country.js (bchavez)

 * Reduce amount of data (LoLFactor)

 * add random vehicle option to _definitions (Tyler Reichle)

 * add vehicle unit tests (Tyler)

 * add make with model and color generators. additional vin numbers (Tyler)

 * add vehicle generator and data (Tyler)

 * add vehicle generator with data (Tyler)

 * Update street_prefix.js (vodasan)

 * [docs] Updating rawgit link (Marak)

 * [misc] Comment out new fields in demo ( for now )   * Won’t be available until next release   * Was causing demo to break #547 (Marak)

 * Add nl_BE locale (Thomas Toye)

 * Indian postcodes are always numeric (KULDIP PIPALIYA)

 * Revert "Update Random to create a per-instance copy of the RNG" (Marak)

 * Update Random to create a per-instance copy of the RNG (Chris Chambers)

 * [minor] Fix typo in code comment (Marak)

 * Add test for setLocale function added in #488 (Ivan Goncharov)

 * [dist] Add vendor folder to test coverage paths (Marak)

 * [test] Added `Faker.unique` test suite #466 (Marak)

 * [api] Unique compare function now configurable   * Can now use custom compare functions   * Improved comments (Marak)

 * hacker ru-locale updates (dhilt)

 * hacker phrase module extract (dhilt)

 * Update Australian postcode ranges (David Beitey)

 * added missing town (Thomas Hochörtler)

 * [dist] Added code coverage tooling   * Adds nyc for code coverage   * Adds coveralls to get repo badge (Marak)

 * [docs] Added Code Coverage badge (Marak)

 * [api] [fix] [minor] Wrong scope for gender (Marak)

 * [api] Added 71 additional gender options   * Adds new gender options for `en` locality   * Updates example page to use gender   * Still needs translations for other locales (Marak)

 * [api] [minor] [refactor]`faker.unique` into class (Marak)

 * [api] First pass at `faker.unique` module   * Adds unique value API for use with any method   * Using in-memory store for unique values   * Provides maxRetries and maxTime options   * RE: #466 #245 #477 (Marak)

 * add alphanumeric symbol * to helpers.replaceSymbols (Iaroslav Popov)

 * Added South African (SA) Locale (Nusrath Khan)

 * Cleanup extra/duplicate lorem/supplemental.js locale files and exports (Sotiris Bakagiannis)

 * Generate an ethereum address (Gokulnath Reddy)

 * Generate a hexaDecimal string (Gokulnath Reddy)

 * Summarize changelog for version 4 (frozenfung)

 * Remove emdash from pl's first_name.js (Pat Tullmann)

 * add missing statement, consistent `=` format (James)

 * Add 'setLocale' method to solve problem with ES6 import (Ivan Goncharov)

 * Add test for faker.date.soon (Alexey Torkhov)

 * Update Readme.md (Alexey Torkhov)

 * Add faker.date.soon method (Alexey Torkhov)

 * require abbreviation removed (AlmazN)

 * rewrite and add some new translation for words (AlmazN)

 * Fix generation of float numbers (Ivan Goncharov)

 * add one more translated word into ru locale (AlmazN)

 * ru index.js ru.hacker field added (AlmazN)

 * added ru locale of hacker dir (AlmazN)

 * add debug info to credit card because of node v0.10 (Jakub Mandula)

 * replace String.prototype.repeat with proper helper (Jakub Mandula)

 * [docs] Updated logo link (Marak)

 * [dist] Update Logo (can anyone make a better one?) (Marak)

 * Add backers and sponsors from Open Collective (Pia Mancini)

 * Delete ES6 (Andres Silva)

 * Add max, min for latitude and longitude (Andres Silva)

 * Set default minimum price to 1 (Jacob Goense)

 * Fix typo in price() description (Jacob Goense)

 * Add ABA routing number (João Fonseca)

 * [dist] Add newest versions of node to .travis.yml   * Added node versions 6 and 6.1   * latest versions offered by travis (cvega)

 * [api] Add `filePath, directoryPath` system methods   * Returns a random path with file name   * Returns a random directory path (no trailing slash) (cvega)

 * fix bug unsplash object (ChinCluBi)

 * remove object.assign.fix unit test (ChinCluBi)

 * added lorempixel and unsplash properties to image obj (ChinCluBi)

 * include image_provider folder to create a doc (ChinCluBi)

 * rewrite build script (ChinCluBi)

 * Comments (Paolo del Mundo)

 * separator enhancements and unit tests (Paolo del Mundo)

 * Add separator (Paolo del Mundo)

 * add node v6.x to travis environment (ChinCluBi)

 * move random image from lorempixel.com to unsplash.com (ChinCluBi)

 * upgrade mocha version to support node v6.x (ChinCluBi)

 * Revert "remove all node_js except 5.1" (amir.8829@gmail.com)

 * remove all node_js except 5.1 (Amirhossein Aleyasen)

 * add comma between entities of street_address.js (amir.8829@gmail.com)

 * remove farsi characters to prevent Unexpected string exception (amir.8829@gmail.com)

 * fix encoding for street_address (amir.8829@gmail.com)

 * add address for fa locale (amir.8829@gmail.com)

 * add String.prototype.repeat in older versions of node - see PR #382 (Jakub Mandula)

 * add tests for credit card functions and helpers (Jakub Mandula)

 * add credit card function + helpers (Jakub Mandula)

 * remove `/` from card formating (Jakub Mandula)

 * add new credit card company (Jakub Mandula)

 * move credit_card into finance + add to definitions (Jakub Mandula)

 * Added unit test for nearbyGPSCoordinate (Vivek Seth)

 * Using different heuristic for producing a random GPS coordinate (Vivek Seth)

 * Ensure longitude points are within range [-180, 180] (Vivek Seth)

 * Fixed bug where variables were being leaked to global namespace (Vivek Seth)

 * If no input params return random coordinate (Vivek Seth)

 * Use term 'coordinate' instead of 'location' (Vivek Seth)

 * Updated readme (Vivek Seth)

 * Added address.nearbyLocation() method (Vivek Seth)

 * add faker.random.arrayElements (Joon Ho Cho)

 * Added gendered names to en locale (Keegan Landreth)

 * Added .npm in .gitignore file (prio101)

 * Add Romanian dates and phone numbers (LoLFactor)

 * Add Romanian addresses (LoLFactor)

 * Add Romanian domain suffixes (internet) (LoLFactor)

 * Add Romanian names (LoLFactor)

 * Use faker.random options dict instead of adding 2 (shadefinale)

 * Edit locales and replaceSymbolwithNumber for more accurate US/CA phone numbers. (shadefinale)

 * Edit locales and replaceSymbolwithNumber for more accurate phone numbers. (shadefinale)


2017-02-21, Version 4.1.0
=========================

 * [dist] Release v4.1.0 (Marak)

 * [dist] Rebuild for new version (Marak)

 * [api] Added bindAll() to Database module #377 (Marak)

 * Functionally test all modules/methods (Jim Fitzpatrick)

 * Statically bind all module methods (Jim Fitzpatrick)


2017-02-20, Version 4.0.0
=========================

 * [dist] Bump to v4.0.0 (Marak)

 * [dist] Rebuild for new version (Marak)

 * [api] [fix] Remove old image links. Closes #464 (Marak)

 * [docs] Remove Patreon link (Marak)

 * [api] [minor] Rename `dataurl` to `dataUri` (Marak)

 * #420 Added dataurl method (Sylvain BANNIER)

 * [api] Added additional https option for imageUrl   * Only covers one image generation method   * Current function signature is bloated   * Needs to be refactored into options hash   * Starts to address #442 (Marak)

 * [test] [fix] [minor] Typo in test name (Marak)

 * Docs: `seed()` is on `faker`, not `random`. (runeh)

 * [dist] Update to latest gulp and mocha (Marak)

 * Fix aomount and price argument dec for case = 0. Add unit tests. Minor codestyle fix. (alexpts)

 * [api] [fix] [minor] Default shuffle value #405 (Marak)

 * [api] Added exports for `az` locality #429 (Marak)

 * Azerbaijani localization has been added (Nurlan Alekberov)

 * [api] [minor] Expose seed option to Faker class   * Closes #456   * Could use additional tests (Marak)

 * [docs] Added section for setting seed #439 (Marak)

 * [api] [fix] Don't allow `/` in file names or paths (Marak)

 * [api] [fix] Typo in require statement (Marak)

 * tests (kulaeff)

 * [api] [fix] Ensure database methods are mapped   * Was causing database methods to fail   * All methods need to be explicitly mapped (Marak)

 * added Database namespace (kulaeff)

 * [refactor] [fix] Move password generator to core   * Migrates password generator from vendor   * Removes erroneous browserifying code   * Switches `Math.random` to faker random   * Closes #460   * Should close #430 (Marak)

 * Fix dec for amount (Alexpts)

 * Don't allow path seperators in generated filenames (Mark Kornblum)

 * Added lorem.slug to functional test (Levente Löki)

 * Added lorem.slug method (Levente Löki)

 * Add .npmignore (David Schovanec)

 * [api] Added `internet.ipv6` method   * Returns a random 8 octet ipv6 address (cvega)

 * [docs] Add Patreon campaign (Marak)

 * Prevented a crash on running helpers.shuffle on an empty array (Ben Douglas)

 * Fix demo URL in Readme (James O'Cull)

 * Adds precision value to faker.random.number call. (Johnny Reina)

 * Add CZ Czech locales (Jakub Mandula)

 * Fix misspelling of 'Liaison' from faker.name.jobType(). (Frankie)

 * Remove duplicate Congo from countries.js (Icebob)

 * Clean up faker.commerce.department method (Konstantin Tarkus)

 * Add IBAN and BIC generator functions (CoDEmanX)

 * Don't change line endings (CoDEmanX)

 * Correct spelling (CoDEmanX)

 * alphaNumeric takes now count as a argument (Krzysztof Kaczor)

 * Update lorem.js (Josh Gordon)

 * New realistic Dutch city naming components (Niels NTG)


2016-03-20, Version 3.1.0
=========================

 * [dist] Bump v3.1.0 (Marak)

 * [dist] Re-build library for v3.1.0 release (Marak)

 * Update tests to confirm name suffix is correct (Logan Allred)

 * Fix name suffixes (Logan Allred)

 * [dist] Added jsdoc and gh-pages to gulpfile   * Will now build jsdocs as part of build   * Will now commit and push jsdocs to gh-pages (Marak)

 * [dist] Switch back to new lodash (Marak)

 * [dist] Remove old versions of node from travis   * Issues with devDeps requirements   * faker API should still work on old versions (Marak)

 * * Use faker.random.number * Range was incorrect. Was 27-36. Should be 27-34. (ashmothership)

 * [fix] [tests] Update lodash API   * .contains() -> .includes() (Marak)

 * [dist] [tests] Adjusting dev dips   * Use new lodash (Marak)

 * [dist] [tests] Less specific loads   * For old node versions (Marak)

 * [dist] [tests] Remove build deps   * Old node versions failing on travois   * gulp tool-chain is too new for old node (Marak)

 * [dist] [tests] Update dev deps   * Trying to get old versions of node to pass (Marak)

 * [test] Comment out finance.bitcoinAddress (Marak)

 * [fix] [revert] finance.bitcoinAddress   * Causing tests to fail   * Not using `faker.random.number` ! (Marak)

 * [fix] Don't pass empty strings to Faker.fake (Marak)

 * [dist] Update to use all node versions (Marak)

 * Bitcoin support (ashmothership)

 * remove Math.random() calls to utilize faker.seed() (Ben Southgate)

 * [dist] [fix] Typo in version number (Marak)

 * [dist] Check /docs back into git #350 (Marak)

 * [fix] Adding missing dependecy #350 (Marak)

 * Install jsdoc and add doclet stubs for all methods (Tobias Witt)

 * Fix  reference in exampleEmail (Jan Alonzo)

 * [docs] Fix a typo in Readme (Prayag Verma)

 * [api] Added `random.locale` method. Closes #274   * Returns a random locale   * May not work correctly in locale builds (Marak)

 * [api] Rename safe_email -> exampleEmail #301   * Public API convention is camelCase   * "example" seemed more explicit than "safe" (Marak)

 * add faker.internet.safe_email (alexei-lexx)

 * [api] [minor] Move semver to System resource #304 (Marak)

 * Added faker.random.semver. (Justin McConnell)

 * [test] [minor] Comment out test (Marak)

 * [api] [fix] Safer Faker.fake call #310   * Removes eval() call from pull request   * eval() is not safe   * Never was actually checked into main repo   * Now uses JSON.parse and fn.apply() (Marak)

 * Remove isolated test (Craig Morris)

 * Support parameters (Craig Morris)

 * [dist] Integrate in-line schemas #170   * Attempts to load any available in-line schemas   * Falls back to using method signature     * Defaults to any type (Marak)

 * [api] [minor] Replace sampleResult #170  * Always return array of samples instead (Marak)

 * [dist] First pass at schema generator #170   * Generates a mschema from faker api   * Useful for auto-documentation   * Starts to provide API contract to all methods (Marak)

 * adding schema for internet.avatar (Cliff Pyles)

 * adding schema for internet.password (Cliff Pyles)

 * adding schema for internet.schema (Cliff Pyles)

 * adding schema for internet.color (Cliff Pyles)

 * adding schema for internet.userAgent (Cliff Pyles)

 * adding schema for internet.ip (Cliff Pyles)

 * adding schema for internet.domainWord (Cliff Pyles)

 * adding schema for internet.domainSuffix (Cliff Pyles)

 * adding schema for internet.domainName (Cliff Pyles)

 * adding schema for internet.url (Cliff Pyles)

 * adding schema for internet.protocol (Cliff Pyles)

 * adding schema for internet.userName (Cliff Pyles)

 * adding schema for internet.email (Cliff Pyles)

 * [fix] Wrong file names in SK locale Closes #336   * Renamed `man` -> `male`   * Renamed `woman` -> `female` (Marak)

 * [api] [minor] Added custom type for commonFileName   * Generates file name based on provided ext (Marak)

 * [api] Better lorem methods   * `lorem.word` no longer returning array   * Adds methods for returning random lorem blocks   * Provides a better variation of results   * Disables some tests ( for now ) (Marak)

 * [api] Improved random methods   * Adds `random.word`   * Adds `random.words`   * Adds `random.image` shortcut (Marak)

 * [api] Added concept of "System" module   * Allows for creation of fake systems data   * So far has file-system related methods     * Mime-types     * File extensions     * File names (Marak)

 * Fix random.uuid not using seeded number generator (John Kurkowski)

 * [Locale: en_GB] Added basic support for generating UK postcodes (Matt Wheatley)

 * Remove Makefile (Jory Graham)

 * [Fix] Display first month as 1 not 0. (beto)

 * [docs] Update README (Marak)

 * Prevent apostrophes in return value of internet#domainWords (yn5)

 * adjust method to allow for gender based prefixes (Carl Sutton)

 * remove title in name (Budi Irawan)

 * add id_ID to lib, create new id_ID js in locale (Budi Irawan)

 * add name locale id_ID (Budi Irawan)

 * Add parameters (Craig Morris)

 * Add swiss names (de_CH) (Daniel Egger)

 * Added LV (Latvian) locale (Anrijs Vitolins)

 * hacker.phrase - generate random string for each lexical instance (Skylar Stein)

 * Added Swedish locale for date (Carl Törnqvist)

 * No space before citySuffix in city name (Pat Tullmann)

 * reinstate mustache example (Iain D Broadfoot)

 * Update meteor package faker npm dependency to v3.0.1 (Ronen Babayoff)

 * Update Travis CI to new container based infrastructure and update travis meteor tests to node v0.10.36 (Ronen Babayoff)

 * Fix meteor package.js to point to lowercased non-default faker Readme.md (Ronen Babayoff)

 * Remove documentation field from meteor package.js - it knows to point automatically to README.md (Ronen Babayoff)

 * Fix meteor package.js git url (Ronen Babayoff)

 * Update meteor package.js file to properly point to faker README (Ronen Babayoff)

 * Add meteor .versions file (Ronen Babayoff)

 * Remove non-breaking spaces from es_MX locale (Jeremy Whitlock)

 * List Greek support to Readme.md (Kostas Bariotis)


2015-07-31, Version 3.0.1
=========================

 * [dist] Bump v3.0.1 (Marak)

 * [dist] Rebuild sources and examples (Marak)

 * Only append suffix to streetName if suffix is present (Tom Collier)

 * [docs] Update README (Marak)

 * Ensure es_MX in main index (Brian Chavez)

 * [docs] Add microservice link (Marak)

 * initial Greek translation (Kostas Bariotis)

 * Adding generators: faker.date.month(), faker.date.weekday() (Michael Radionov)

 * through2 dependency added to devDependencies (Kostas Bariotis)

 * fixed sentence formatting (Brandon Dail)

 * cleaned up files (Brandon Dail)

 * Removed built files (Brandon Dail)

 * Reverted build so it wasn't specific to my system (Brandon Dail)

 * Implemented faker.seed method for randomization seeding (Brandon Dail)

 * Add catalog es_MX (IORTREGA)

 * [docs] [fix] Documentation generator is removing example mustache syntax (Marak)


2015-07-09, Version 3.0.0
=========================

 * [dist] Bump to v3.0.0 (Marak)

 * [dist] Regenerate build. Prep for release. (Marak)

 * [test] [fix] Remove test for legacy method. (Marak)

 * Adding en_IE (Ireland) locale resolves #235 (Barry Gallagher)

 * Added en_IE (Ireland) locale (Barry Gallagher)

 * [examples] Update UI for browser example page. (Marak)

 * [api] [refactor] Rename `array_element` and `object_element` to camelCase. Set default max random number to 99999. Added default arguments to some methods. (Marak)

 * [fix] Comment out a few methods sections of commerce section. Needs some work. #183 (Marak)

 * [docs] Updating README (Marak)

 * [fix] [api] Add back commerce methods. (Marak)

 * [docs] Update README (Marak)

 * * Fixed up assertions. (portse)

 * * Added unit tests as per request in PR comment. (portse)

 * [docs] [fix] ReadMe (Marak)

 * * Removed import of the zipFormat module. (portse)

 * * Removed unused zipFormat definition from the 'en' locale. (portse)

 * When the locales were split out (commit: 760e50ff2d04a95c990aff98ab84a6c17fb3854c), the en_CA locale lost its zipFormat definition added in PR #173. * Reverted back to simply using the postcode definition. * Updated zipCode function to use that definition for the locale. * Ensure en_CA locale has a postcode definition file. (portse)

 * [dist] Re-build library and all new locale packs (Marak)

 * [dist] Update examples (Marak)

 * [docs] Updating README and build script. (Marak)

 * [test] Comment out commerce test ( for now ) (Marak)

 * [refactor] [major] Adds incremental browser builds. Switch to using prototype for internal API. Previous usage of `module.parent` is not acceptable. Locale information is now passed into Faker constructor. Closes #125 (Marak)

 * [refactor] [dist] Allow for node to require individual locales ( to avoid the default behavior of requiring all locale data. #125 #167 (Marak)

 * [fix] [api] Add title and separator properties to locales. Allow for mapping of string properties. Add missing categories property. (Marak)

 * [fix] [minor] Off by 1 error (Marak)

 * [refactor] [locales] Split all locale data into separate modules. Closes #203 (Marak)

 * username must be a string (Andrey Khomenko)

 * [merge] Canadian zip codes (Marak)

 * [merge] Support gender in names (Marak)

 * [merge] Commerce implementation (Marak)

 * [merge] country_code branch (Marak)

 * [merge] Add basic Ukrainian support (Marak)

 * [merge] [api] Added missing street prefix method (Marak)

 * [fix] [minor] Typo (Marak)

 * [merge] [api] Add name.jobTitle (Marak)

 * [docs] Update travis link. Closes #131 (Marak)

 * [docs] Update README Closes #129 (Marak)

 * [merge] [dist] Package faker for meteor.js (Marak)

 * [api] [fix] Remove tabs from paragraph generation. Make paragraph separator configurable. Closes #223 (Marak)

 * [api] [refactor] Replaced switch / cases and string concats with Faker.fake method. #199 (Marak)

 * [minor] Change order of require (Marak)

 * [api] [refactor] [fix] Begin switch to using Faker.fake generator for all string concats. Replaced switch / case statements with formatting arrays. Closes #226 (Marak)

 * [fix] Add fake require (Marak)

 * [api] First pass at generators with mustache strings. #226 #199 #171 #224 (Marak)

 * Update locales.js (Pier-Luc Gendreau)

 * Create fr_CA.js (Pier-Luc Gendreau)

 * Add basic Ukrainian support and bugfixes (Anatoliy Yevpack)

 * Fixing method name references to mac generator in tests (João Ferreira)

 * Including a MAC Address generator (João Ferreira)

 * [dist] Bump to v2.1.5 (Marak)

 * create title function (Ivan Velasquez)

 * add faker.name.title() tests (Ivan Velasquez)

 * resolves #176 Add random boolean generator (Alan Shaw)

 * Adding test for negative minimum and max = 0 (Phil Greenberg)

 * Fixing bug in random.number when max = 0 (Phil Greenberg)

 * Remove moot `version` property from bower.json (Kevin Kirsche)

 * [dist] Bump to v2.1.4 (Marak)

 * Fix issue Marak/faker.js#214 with shuffle() (Sherman Mui)

 * Update license property (Peter deHaan)

 * Additional data for Georgian (Levan Velijanashvili)

 * Add more names (females) (Levan Velijanashvili)

 * Add more names (males) (Levan Velijanashvili)

 * [dist] Bump v2.1.3 (Marak)

 * [minor] Copy update (Marak)

 * preparing release v2.1.3 (Tomasz Ducin)

 * added badge fury #177 (Tomasz Ducin)

 * updated readme: sources and generated content #170 (Tomasz Ducin)

 * added CONTRIBUTING.md file for better community contribution #170 (Tomasz Ducin)

 * Update ReadMe.md (Marak)

 * random.uuid added to docs, issue #192 (Tomasz Ducin)

 * Remove duplicate data property in object literal (Evan Sharp)

 * Fix random number unit test spec (Evan Sharp)

 * Fixed color copy-paste (Jevgeni Smirnov)

 * Updated README, specifically the API documentation so that every function has its usage and output (rob.scott)

 * npm version updated (rob.scott)

 * Added Turkish locales. (Oguzhan Demir)

 * Add zh_TW locale (Dca)

 * More readable gender choosing (Marat Dyatko)

 * Russian names have no prefixes and suffixes (Marat Dyatko)

 * Define male and female names (Marat Dyatko)

 * Support gender in names (Marat Dyatko)

 * Implemented proper formatting of Canadian postal codes (remains address.zipCode in the API) when locale is set to en_CA. address.zipCode also now accepts a zip format string, so that a user can specifically specify the format they wish to see. If this is not passed in, a locale based zip format string is used. This will keep the concerns of zipCode formatting specific to the locales. (portse)

 * Updated en_CA locale file to reflect corrected official abbreviation for Yukon. (portse)

 * Corrected abbreviation for Yukon to reflect its official abbreviation of "YT". (portse)

 * Update nl.js (Joshua Thijssen)

 * added protocol() and url() (Daniel Mills)

 * Remove duplicate city in georgian (Levan Velijanashvili)

 * Added some more data to georgian locale (Levan Velijanashvili)

 * Require georgian in locales.js (Levan Velijanashvili)

 * Missing newline at the end (Levan Velijanashvili)

 * Georgian locale fixes (Levan Velijanashvili)

 * Add georgian phone numbers (Levan Velijanashvili)

 * Add georgian internet (Levan Velijanashvili)

 * Add georgian addresses (Levan Velijanashvili)

 * Add georgian last names and job titles (Levan Velijanashvili)

 * Add georgian locale (Levan Velijanashvili)

 * fix random number bug (with {max: 0}) (linkkingjay)

 * Add new jobTitle function to name object. (JKillian)

 * Make company suffix function use data from locale instead of hard-coded data. (jkillian)

 * Fasten travis meteor tests by not starting a meteor mongodb (Ronen Babayoff)

 * Try and fix .travis.yml (Ronen Babayoff)

 * Try and fix travis (Ronen Babayoff)

 * Fix .travis.yml (Ronen Babayoff)

 * Remove and ignore meteor versions.json (Ronen Babayoff)

 * Package for meteor, including testing the meteor package in travis (Ronen Babayoff)

 * adds ability to get random country code and tests. (FotoVerite)

 * Added street suffix (Yann Barraud)

 * Added missing street prefix method (Yann Barraud)


2015-03-12, Version 2.2.2
=========================

 * Adjusted the random test on an object as the random number generator is inclusive of the max number, so sometimes the test would fail. (rob.scott)

 * Replaces symbols in domain words so it generates output for all locales (rob.scott)

 * removes a console.log when generating a price (rob.scott)


2015-03-10, Version 2.2.1
=========================

 * Updated README to an actual markdown format. (rob.scott)


2015-03-10, Version 2.2.0
=========================

 * Removed trailing comma (rob.scott)

 * Add Commerce functions from https://github.com/stympy/faker into javascript (rob.scott)


2015-06-11, Version 2.1.5
=========================

 * [dist] Bump to v2.1.5 (Marak)

 * create title function (Ivan Velasquez)

 * add faker.name.title() tests (Ivan Velasquez)

 * resolves #176 Add random boolean generator (Alan Shaw)

 * Adding test for negative minimum and max = 0 (Phil Greenberg)

 * Fixing bug in random.number when max = 0 (Phil Greenberg)

 * Remove moot `version` property from bower.json (Kevin Kirsche)

 * Update license property (Peter deHaan)

 * Additional data for Georgian (Levan Velijanashvili)

 * Add more names (females) (Levan Velijanashvili)

 * Add more names (males) (Levan Velijanashvili)

 * Added Turkish locales. (Oguzhan Demir)

 * Add zh_TW locale (Dca)

 * added protocol() and url() (Daniel Mills)

 * Remove duplicate city in georgian (Levan Velijanashvili)

 * Added some more data to georgian locale (Levan Velijanashvili)

 * Require georgian in locales.js (Levan Velijanashvili)

 * Missing newline at the end (Levan Velijanashvili)

 * Georgian locale fixes (Levan Velijanashvili)

 * Add georgian phone numbers (Levan Velijanashvili)

 * Add georgian internet (Levan Velijanashvili)

 * Add georgian addresses (Levan Velijanashvili)

 * Add georgian last names and job titles (Levan Velijanashvili)

 * Add georgian locale (Levan Velijanashvili)


2015-06-04, Version 2.1.4
=========================

 * [dist] Bump to v2.1.4 (Marak)

 * Fix issue Marak/faker.js#214 with shuffle() (Sherman Mui)


2015-05-11, Version 2.1.3
=========================

 * [dist] Bump v2.1.3 (Marak)

 * [minor] Copy update (Marak)

 * preparing release v2.1.3 (Tomasz Ducin)

 * added badge fury #177 (Tomasz Ducin)

 * updated readme: sources and generated content #170 (Tomasz Ducin)

 * added CONTRIBUTING.md file for better community contribution #170 (Tomasz Ducin)

 * Update ReadMe.md (Marak)

 * random.uuid added to docs, issue #192 (Tomasz Ducin)

 * Remove duplicate data property in object literal (Evan Sharp)

 * Fix random number unit test spec (Evan Sharp)

 * Fixed color copy-paste (Jevgeni Smirnov)

 * Update nl.js (Joshua Thijssen)


2015-01-07, Version 2.1.2
=========================

 * [dist] Bump v2.1.2 (Marak)

 * Added function to generate UUID (James Drew)

 * Added unit test for uuid generator (James Drew)

 * update documentation of array_element (Andreas Böhrnsen)


2014-11-29, Version 2.1.1
=========================

 * [dist] Bump to v2.1.1 (Marak)

 * added tests and corrected the number function (Michał Kawalec)

 * precision changes precision and max doesn't modify options object (Michał Kawalec)

 * Fixed male/female split check on findName() (Ari Gesher)

 * Ensure that colours are always of the form #RRGGBB (Filip Wieland)


2014-11-19, Version 2.1.0
=========================

 * [dist] Bump to v2.1.0 (Marak)

 * Have past, future and recent return random dates (Daniel Perez Alvarez)


2014-11-17, Version 2.0.3
=========================

 * [dist] Bump to v2.0.3 (Marak)


2014-11-17, Version 2.0.2
=========================

 * [dist] Bump to v2.0.2 (Marak)

 * Update bower.json (Jonathan Bonnefoy)

 * [examples] Clean up min example (Marak)

 * [fix] ru locale now works with name.firstName and name.lastName methods #132 (Marak)

 * [dist] Fix project name (Marak)


2014-09-22, Version 2.0.0
=========================

 * [fix] state_abbr -> stateAbbr (Marak)

 * [dist] [fix] Package name (Marak)

 * [docs] Add demo link (Marak)

 * [docs] Update travis image (Marak)

 * [dist] Release v2.0.0 (Marak)

 * [dist] Rebuild (Marak)

 * [fix] Rename state_abbr to stateAbbr (Marak)

 * [api] [minor] Add back state_abbr. (Marak)

 * [fix] Date.past #110 (Marak)

 * [dist] Updated browser example. Moved browser example into new directory. (Marak)

 * [api] [minor] Added default values for more methods. Cleaned up image module. Use a less specific regex for usernames. (Marak)

 * [data] Added locale titles (Marak)

 * [api] Added internet.password method using `password-generator` library. [dist] Added `password-generator` to vendor Closes #33 (Marak)

 * [api] Removed tree module. This code should be in a separate project. (Marak)

 * [api] Added hacker module. Added default values for all methods. Cleaned up errant methods. Added mustache helper. (Marak)

 * [feature] - add faker for currency (MQuy)

 * [api] Add ability to generate contextual data for user names and emails. #68 (Marak)

 * [dist] Removed upper case Faker from last sources. Project is now renamed on Github. (Marak)

 * [fix] Prevented emails and userNames from including generally unacceptable characters such as apostrophes, which occur semi-regularly when Faker generates last names such as "o'hara". Conflicts: 	Faker.js 	lib/internet.js (Tim Oxley)

 * replaced string[index] with charAt - issue 91 (beastlike)

 * [dist] Update mocha (Marak)

 * [tests] [fix] Set locale back to en to make phone test pass (Marak)

 * [api] Require all locales by default (Marak)

 * [examples] Added drop down for locale selection (Marak)

 * [api] [refactor] Removed definitions.js file. All data definitions are now loaded from localized data sets, en is default locale. #116 (Marak)

 * [dist] Changes package.json to point to Marak/Faker.js again. (FotoVerite)

 * [docs] Adds badge to Readme and turns off 0.8 testing for the moment. (FotoVerite)

 * [refactor] [major] Renamed variable names for consistency Closes #5 [refactor [major] Moved all errant methods from random.js to individual modules. Methods in random.js were causing unnecessary code complication. (Marak)

 * [api] First pass at adding localization data definitions. #116 (Marak)

 * [dist] Updated license to give more specific attribution to original Faker projects (Marak)

 * [api] Added Internet.userAgent #16 (Marak)

 * [api] Added basic financial generators Closes #32 Merge https://github.com/josefsalyer/Faker.js (Marak)

 * [dist] [refactor] Replace legacy build system with Gulp and Browserify. #61 #85 #116 (Marak)

 * [api] [refactor] Random.number is now powered by node-mersenne instead of Math.random() #48 (Marak)

 * [api] [refactor] Replaced Math.Random calls with Random.number. Random ranges are now inclusive of max instead of exclusive. #88 #48 (Marak)

 * [fix] Do not serialize Dates from Date.random APIs. Dates are now returned as Date objects. #93 (Marak)

 * Fix random number (Marak)

 * Remove this scope from new phone codes (Marak)

 * add faker for phone code Conflicts: 	lib/definitions.js (MQuy)

 * Fix: faker.Lorem.sentence() was ignoring the 'range' parameter. (Foster Hersey)

 * refactor avatar url to reduce size of definitions (MQuy)

 * Rebuild (Marak)

 * Add bower.json file. Added namespace for AMD definition ( by request, not fully tested ) #77 (Marak)

 * Create bower package file (Dayton Nolan)

 * Fixed errant require in example (Marak)

 * Removed "this" from functions, breaks mixins (goliatone)

 * I forgot how much of stinker zero is in Javascript. Looping tests on finance should no longer fail (Josef Salyer)

 * fixed linting issues in lib/finance.  TODO: automate this as part of the tests? (Josef Salyer)

 * updated Readme.md (Josef Salyer)

 * added tests and cleaned up at 100% in istanbul (not constantinople) (Josef Salyer)

 * added a bunch of test, changed format of many files to match the newer style (Josef Salyer)

 * removed fako tests (Josef Salyer)

 * added to node lib. all tests pass (Josef Salyer)

 * added some additional notes about the amount helper (Josef Salyer)

 * added amount in (Josef Salyer)

 * added some simple helpers for the financial industry (Josef Salyer)

 * starting on structure for financial mocking (Josef Salyer)


2014-08-13, Version 1.1.0
=========================

 * Version 1.1.0 is the lastest. (FotoVerite)

 * Fixes syntax on changelog. (FotoVerite)

 * Bump version to 1.1.0. (FotoVerite)

 * All changes to faker will now include a changelog. (FotoVerite)

 * Undefined global object for webworker fix contributed by dnbard (FotoVerite)

 * BUILD added successfully. (FotoVerite)

 * Fix context of findName (Juan Pablo)

 * Add installation instructions for npm (Khalid Jebbari)

 * Fixes link to Ruby Gem faker (Javier Cejudo)

 * Fixes link to Data::faker (Javier Cejudo)

 * Updates to switch changes over to using 2 args to support min/max (Anthony van der Hoorn)

 * Better UMD (Universal Module Definition) support (Pavel Strashkin)

 * Fixed random date functions that did not distribute results evenly over the requested period. (pmalouin)


2014-07-22, Version 1.0.1
=========================

 * Bug fixes and latest version. (FotoVerite)

 * random number now accepts a range array [min, max]. (Ed Shadi)

 * added hours in date.recent. Currently the code returns date in past minutes. random days could return 0 so modified the test to reflect <= current date. (Ed Shadi)

 * Ensure Date.future returns a date in the future. (Shane A. Stillwell)


2014-05-17, Version 1.0.0
=========================

 * All files are now lowercased. :D (FotoVerite)

 * deletes the last Uppercase faker file. (FotoVerite)

 * We need remove these versions because of mac os case stupidity. (FotoVerite)

 * Moving to major new version for change of package name for uppercase to lowercase. (FotoVerite)

 * Adds female and male name methods. #NOTE they will return a random name and working as intended. (FotoVerite)


2014-05-17, Version 0.7.2
=========================

 * Bumps version number and rebuilds (FotoVerite)

 * better version handling:   * 'Faker.version' will now be populated by the version property in 'package.json' (hkal)

 * run build to reflect latest changes:   * should reflect changes from 10181fbf6c1e7fa334fa0b86935326c140bee830   * should reflect changes from 272cd8e1e1fa7a504326b3f3ed5cd75151429977 (hkal)

 * Updates Build. (FotoVerite)

 * auto-increment copyright year in docs (hkal)

 * remove gender related files:   * removed files relating to gender   * removed an esoteric `import.js` file which did not seem to be used (hkal)

 * improve image test coverage (hkal)

 * functions should reference current literal:   * fixes error: 'Uncaught ReferenceError: image is not defined Faker.js:275' (hkal)

 * removes gender tests. (FotoVerite)

 * Removes gender. Score 1 for non binary fake data. (FotoVerite)

 * reverts f2f37f8 (FotoVerite)

 * Updates the Readme. (FotoVerite)

 * I'm an idiot lets make sure that the package is right this time. (FotoVerite)


2014-02-17, Version 0.6.1
=========================

 * bumps version. (FotoVerite)

 * Add Date functionality: past, future, recent, between (cyanos3)

 * Build containing male/female separation (Jay Liu)

 * Remove extraneous files (cyanos3)

 * My take on separating male and female names. Tests passing, Coverage restored. (cyanos3)

 * Update build with Tree module supporting width function (Jay Liu)

 * Tree: let the width parameter also be a function that returns an int (cyanos3)

 * Update build with (working) Tree module (Jay Liu)

 * Refactor tree so that it will work with the module model. (Not working at all prior) (cyanos3)

 * Adding Internet.color to build (Jay Liu)

 * Add random color to Internet.js (cyanos3)

 * Include Tree in build (Jay Liu)

 * Add tree: (cyanos3)

 * Pretty print names files (Richard Butler)

 * Update package.json (Richard Butler)

 * Add gender to name class (Richard Butler)

 * Add random gender (Richard Butler)

 * Split male and female names into two groups (Richard Butler)


2014-02-17, Version 0.6.0
=========================

 * More updating to get things inline. (FotoVerite)

 * fixes travis.yml to actually run. (FotoVerite)

 * Updates location of Faker to FotoVerite. (FotoVerite)

 * Fixes so build runs. (FotoVerite)


2014-02-17, Version 0.5.12
==========================

 * bumps version to 0.5.12 (FotoVerite)

 * update copyright year (PatrickJS)

 * Add UIFaces to generate random avatar (Kieu Anh Tuan)

 * Add support to lorempixel image provider (Kieu Anh Tuan)

 * [Version, hot-fix] working 0.5.11 (dmamills)


2013-06-12, Version 0.5.11
==========================

 * [Version, hot-fix] working 0.5.11 (FotoVerite)

 * Revert "Merge pull request #59 from rschmukler/this-fix" (FotoVerite)

 * [util] merged in chrisocast changes, updated build and version. (FotoVerite)

 * [build] new build created for version 0.5.9 (FotoVerite)

 * Switched from this to var name to avoid context issues (Ryan Schmukler)

 * Add range param to lorem.sentence (Chris Cast)


2013-06-12, Version 0.5.9
=========================

 * [Version] bumped version (FotoVerite)

 * [package] Updates package.json to run tests with npm test. (FotoVerite)

 * [version] bumped version (FotoVerite)

 * Improve perf by declaring definitions as arrays (Joel Fillmore)

 * fix #35: Add latitude/longitude fields (address.geo.[lat/lng]) (Mikhail Fedosov)

 * js cleanup (jshint) (Mikhail Fedosov)


2013-03-15, Version 0.5.7
=========================

 * [version] Bumped Version (FotoVerite)

 * [fix] fixes address module switch cases (FotoVerite)

 * fix #42: Email has invalid characters (Mikhail Fedosov)

 * incremented version (FotoVerite)

 * fixed typo for windows machines (FotoVerite)

 * changed main to index as is common  node style (FotoVerite)

 * re-build (Bryan Donovan)

 * adding randomNumber and randomize back to helpers.js (Bryan Donovan)

 * Fixing merge conflicts from upstream (Bryan Donovan)

 * rebuilt (FotoVerite)

 * fixed broken faker clouser and street address function from busted pull request. (FotoVerite)

 * updated readme not to have outdated link (FotoVerite)

 * added minified version (FotoVerite)

 * fixed package.json (FotoVerite)

 * commenting out faker closure to get browser test to work (Bryan Donovan)

 * allowing all tests to run in browser (Bryan Donovan)

 * adding real browser tests (Bryan Donovan)

 * renaming array_rand to array_element (Bryan Donovan)

 * bumping test coverage thresholds (Bryan Donovan)

 * 100% test coverage. (Bryan Donovan)

 * phone number tests (Bryan Donovan)

 * lorem.js tests (Bryan Donovan)

 * style change (Bryan Donovan)

 * linting and getting address.js to 100% test coverage (Bryan Donovan)

 * cleanup old code (Bryan Donovan)

 * adding test run instructions to docs (Bryan Donovan)

 * working browser test (Bryan Donovan)

 * making company.suffixes a function in tests (Bryan Donovan)

 * using this instead of _name for internal references (Bryan Donovan)

 * making company.suffixes a function (Bryan Donovan)

 * adding make build target (Bryan Donovan)

 * Completely removing aliased lower-case functions (Bryan Donovan)

 * namespacing with 'Faker' (Bryan Donovan)

 * reverting downcasing (Bryan Donovan)

 * .jshintrc cleanup (Bryan Donovan)

 * backward-compat tests (Bryan Donovan)

 * lower-casing modules (Bryan Donovan)

 * lower-case module names (Bryan Donovan)

 * brState() tests (Bryan Donovan)

 * tests for streetAddress() (Bryan Donovan)

 * initial address.unit.js (Bryan Donovan)

 * adding functional test for each function (Bryan Donovan)

 * refactoring to use random.js (Bryan Donovan)

 * refactoring so we do not need to use Helpers.randomize() everywhere (Bryan Donovan)

 * refactoring company.js (Bryan Donovan)

 * 100% coverage on company.js (Bryan Donovan)

 * refactored name.js (Bryan Donovan)

 * adding mocha test runner (Bryan Donovan)

 * adding test/name.unit.js (Bryan Donovan)

 * partially linted Faker.js file (Bryan Donovan)

 * ignoring coverage dir (Bryan Donovan)

 * renaming tests dir to test (Bryan Donovan)

 * adding tests/run.js (Bryan Donovan)

 * linted address.js (Bryan Donovan)

 * linted company.js (Bryan Donovan)

 * ignoring linting of lib/definitions.js (Bryan Donovan)

 * linted helpers (Bryan Donovan)

 * linted internet.js (Bryan Donovan)

 * linted lorem.js (Bryan Donovan)

 * linting name/phone_number (Bryan Donovan)

 * linted phone_number.js (Bryan Donovan)

 * adding .jshintrc and Makefile (Bryan Donovan)

 * fixed build script, removed a pointless trailing slash (DimitarChristoff)

 * change to support amd, modules.export only Faker and Faker to global otheriwse. change domains - removed .uk and added biz, io, me, net, org (DimitarChristoff)

 * massive refactor of all sub modules and rebuild to remove syntax errors and jshint issues (DimitarChristoff)

 * node test as shell script (DimitarChristoff)

 * fixes for trailing commas and redundant local declarations of arguments for jshint love (DimitarChristoff)

 * [docs] Removed old link (Marak Squires)


2012-08-24, Version 0.5.5
=========================

 * First release!
