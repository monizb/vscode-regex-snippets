<p align="center">
<img src="https://firebasestorage.googleapis.com/v0/b/survey-tool-43d04.appspot.com/o/baked.png?alt=media&token=b603440e-589a-460c-9577-a85b0fdeb1ad" alt="drawing" width="100"/>
</p>

# Regex Snippets

![Version](https://vsmarketplacebadge.apphb.com/version/Monish.regexsnippets.svg)
![Downloads](https://vsmarketplacebadge.apphb.com/downloads/Monish.regexsnippets.svg)
![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
[![GitHub license](https://img.shields.io/github/license/thedevs-network/kutt.svg)](https://github.com/monizb/vscode-regex-snippets/blob/master/LICENSE.md)
![Issues](https://img.shields.io/github/issues/monizb/vscode-regex-snippets)
![Last Commit](https://img.shields.io/github/last-commit/monizb/vscode-regex-snippets)

A VS Code Extension with a list of 50+ hand picked Regex Code Snippets to make
lives of many Developers much easier.

Check it out here:
https://marketplace.visualstudio.com/items?itemName=Monish.regexsnippets

### Why This Extension?

There are no extensions for Regular Expressions Snippets on the Marketplace
right now, this extension provides the most commonly used Regex Snippets so that
you don't have to memorize the difficult syntax which in turn reduces
development time.

### How Does It Work?

#### Method 1

1. From the command palette `Ctrl+Shift+P` (Windows, Linux) or `Cmd+Shift+P` (OSX)
2. Type `Insert Snippet` then select `Insert Snippet` ![image](https://user-images.githubusercontent.com/94578938/172023525-bdfe4203-494b-4c28-8e85-d61ece2924a1.png)
3. Type `!` and you will get the list of available snippets ![image](https://user-images.githubusercontent.com/94578938/172023558-1fdaaf3b-c939-4f8c-8618-15c7797d76b2.png)

#### Method 2

1. In the editor, type `!` then hit `Ctrl+Space`
2. Select the snippet you want, eg: `!addlinktag`
   ![image](https://user-images.githubusercontent.com/94578938/172023427-8598cc67-d119-437f-9578-0c417b35cba7.png)

### Snippets

The following table shows all the 50+ code snippets included within this
extension

| Sl No. | Prefix                | Description                                                                                                                                     | Input Required                                                                                                   |
| ------ | --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| 1      | `!valemail`           | Email Address Validation                                                                                                                        | N/A                                                                                                              |
| 2      | `!valhexcol`          | Hexadecimal Color Validation                                                                                                                    | N/A                                                                                                              |
| 3      | `!valpass`            | Password Validation (1 uppercase, 1 lowercase, 1 number, 1 special)                                                                             | 2 Inputs: `min` and `max` length for the password                                                                |
| 4      | `!valisbn`            | ISBN Number Validation                                                                                                                          | N/A                                                                                                              |
| 5      | `!valipv4`            | IPV4 Address Validation                                                                                                                         | N/A                                                                                                              |
| 6      | `!valipv6`            | IPV6 Address Validation                                                                                                                         | N/A                                                                                                              |
| 7      | `!valmmddyy`          | Date Validation In mm/dd/yy format (Separator does not matter)                                                                                  | N/A                                                                                                              |
| 8      | `!valmonddyyyy`       | Date Validation In mon/dd/yyyy format (Ex: Jan/23/2001, Separator does not matter)                                                              | N/A                                                                                                              |
| 9      | `!valmonth`           | Month Validation (Both Full and Abbreviated Form, Ex: Jan(uary))                                                                                | N/A                                                                                                              |
| 10     | `!extprice`           | Extract Price Value from any string                                                                                                             | 1 Input: `currency_symbol` for the currency you want to use                                                      |
| 11     | `!parehead`           | Parse an Email Header to retrieve "To" address                                                                                                  | N/A                                                                                                              |
| 12     | `!valfbllink`         | Check if the given Facebook Profile Link is valid                                                                                               | N/A                                                                                                              |
| 13     | `!valcc`              | Credit Card Validation (Does not check for fake numbers) Supported Cards: Visa, MasterCard, American Express, Diners Club, Discover, and JCB    | N/A                                                                                                              |
| 14     | `!valusername`        | Username Validation with minimum and maximum characters                                                                                         | 2 Inputs: `MIN_CHARS` and `MAX_CHARS`                                                                            |
| 15     | `!exturl`             | Extract URLs from a string                                                                                                                      | N/A                                                                                                              |
| 16     | `!getiever`           | Get the current Internet Explorer Version being used                                                                                            | N/A                                                                                                              |
| 17     | `!valimage`           | Validate image filenames (Remove/ADD extensions as required)                                                                                    | N/A                                                                                                              |
| 18     | `!valcityabbr`        | Validate City Names (Or any words) with First 2 letters abbreviated (Ex: India, IN)                                                             | N/A                                                                                                              |
| 19     | `!valusphone`         | US Phone Number Validation                                                                                                                      | N/A                                                                                                              |
| 20     | `!valssn`             | Social Security Number Validation                                                                                                               | N/A                                                                                                              |
| 21     | `!valhtmlcont`        | Verify if the given string contains content between the provided html tags (Ex: `<p>Hello</p>`)                                                 | 1 Input: `tag_name` for the HTML Tag you want to search for                                                      |
| 22     | `!valhtmltag`         | Validates if the given string has either a opening or closing HTML tag (Does not verify if the HTML Tag exists)                                 | N/A                                                                                                              |
| 23     | `!valtwitter`         | Twitter Username Validation                                                                                                                     | N/A                                                                                                              |
| 24     | `!valurl`             | URL Validation                                                                                                                                  | N/A                                                                                                              |
| 25     | `!valgooglesyn`       | Google Search Syntax Validation                                                                                                                 | N/A                                                                                                              |
| 26     | `!extcssmedia`        | Extract properties and values from CSS Media Queries                                                                                            | N/A                                                                                                              |
| 27     | `!exthtmlcomms`       | Strip all comments from a HTML Code Block                                                                                                       | N/A                                                                                                              |
| 28     | `!extcss`             | Extract Individual CSS Properties from the given Code Block                                                                                     | N/A                                                                                                              |
| 29     | `!extytid`            | Extract Video ID from a valid Youtube Video Link                                                                                                | N/A                                                                                                              |
| 30     | `!extimgsrc`          | Extract image source links from HTML Image Tags                                                                                                 | N/A                                                                                                              |
| 31     | `!valbase64`          | Base64 String Validation                                                                                                                        | N/A                                                                                                              |
| 32     | `!septhousand`        | Seperates the digits in the string to thousand with commas                                                                                      | N/A                                                                                                              |
| 33     | `!valchars`           | Validate if the the string contains atleast one occurrence of the Character to be searched                                                      | 1 Input: `chars_to_be_searched`                                                                                  |
| 34     | `!valspaces`          | Convert multiple spaces to single spaces between each word in a string                                                                          | N/A                                                                                                              |
| 35     | `!extsqrbracks`       | Extract Square Brackets and the content between them                                                                                            | N/A                                                                                                              |
| 36     | `!valalpnum`          | Non-Alphanumeric Characters Validation                                                                                                          | N/A                                                                                                              |
| 37     | `!extlogs`            | Extract native Javascript console and AngularJS \$log log warn or info that are NOT comments / commented out                                    | N/A                                                                                                              |
| 38     | `!extbrackscont`      | Extract all brackets and the content between them                                                                                               | N/A                                                                                                              |
| 39     | `!addlinktag`         | Adds Link Tags to all the strings that start with http or https (Full Function Provided)                                                        | N/A                                                                                                              |
| 40     | `!findocurrences`     | Provides a function to calculate the number of times the provided character(s) have appeared in the string (Returns 0 when no ocurrences found) | 2 Inputs: `string` on which the match should be applied and `string_to_search` for the string to be searched for |
| 41     | `!valuuidv1`          | UUID v1 Validation                                                                                                                              | N/A                                                                                                              |
| 42     | `!valuuidv2`          | UUID v2 Validation                                                                                                                              | N/A                                                                                                              |
| 43     | `!valuuidv3`          | UUID v3 Validation                                                                                                                              | N/A                                                                                                              |
| 44     | `!valuuidv4`          | UUID v4 Validation                                                                                                                              | N/A                                                                                                              |
| 45     | `!valuuidv5`          | UUID v5 Validation                                                                                                                              | N/A                                                                                                              |
| 46     | `!extquotes`          | Extracts any text between quotations (Works with nested quotes too)                                                                             | N/A                                                                                                              |
| 47     | `!splitnchunks`       | Splits the given string to n-sized chunks even if its size is not an exact multiple                                                             | 1 Input: `end_size` for chunk size                                                                               |
| 48     | `!valzip`             | Zip Code(5 or 9 digits only) Validation                                                                                                         | N/A                                                                                                              |
| 49     | `!valendswith`        | Check if the provided string ends with the given Character                                                                                      | 1 Input: `character` which the string should end with                                                            |
| 50     | `!extdomain`          | Extract the domain from a valid URL string                                                                                                      | N/A                                                                                                              |
| 51     | `!tocamel`            | Returns a function which converts the given string to camelCase                                                                                 | 1 Input: `string` to be replaced                                                                                 |
| 52     | `!valjwt`             | Validates if the given string is a valid JSON Web Token (JWT)                                                                                   | N/A                                                                                                              |
| 53     | `!valjson`            | Validates if the given string is a valid Non-array JSON                                                                                         | N/A                                                                                                              |
| 54     | `!valspecialusername` | Validates if the given string is in the form of test@test                                                                                       | N/A                                                                                                              |
| 55     | `!multispace`         | Replaces all the spaces in the given string with a single space                                                                                 | N/A                                                                                                              |
| 56     | `!nonalphanumeric`    | Replaces all the non-alphanumeric characters in the given string with a single space                                                            | N/A                                                                                                              |
| 57     | `!blankline`          | Validates if the given string is blank line                                                                                                     | N/A                                                                                                              |
| 58     | `!positiveint`        | Checks if the given string is a valid positive integer                                                                                          | N/A                                                                                                              |
| 59     | `!positivedecimal`    | Validates if the given string is a valid positive decimal                                                                                       | N/A                                                                                                              |
| 60     | `!positivedecimal1`   | Validates if the given string is a valid positive decimal with a single decimal digit                                                           | N/A                                                                                                              |
| 61     | `!ssn`                | Validates if the given string is a valid Social Security Number                                                                                 | N/A                                                                                                              |
| 62     | `!valdate`            | Validate if the given string is a valid date                                                                                                    | N/A                                                                                                              |
| 63     | `!replacefont`        | Replaces all the font tags in the given string with a single space                                                                              | N/A                                                                                                              |

### Installation

Requires VS Code Version `1.20.0` atleast

1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl+Shift+P` (Windows, Linux) or
   `Cmd+Shift+P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code
7. Optionally find the extension file
   [here](https://github.com/monizb/vscode-regex-snippets/blob/master/regexsnippets-1.0.2.vsix)
   , launch VS Code , Goto the extensions tab click the 3 dots on top, Click
   install from VSIX File, Choose the downloaded file and done!

### Contribution

Any and every contribution to this repoitory is welcomed, if you would like to
add new features, file a bug report or make contribution, please first create an
issue using the appropriate template.

### Author

Monish Basaniwal
