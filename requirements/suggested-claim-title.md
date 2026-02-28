# Suggested Claim Title

|                           |                                    |
| ------------------------- | ---------------------------------- |
| **What**                  | A feature for the ClaimStation App |
| **Target Repo**           | `claimstation-app`                 |
| **Implementation Status** | Not started                        |
|                           |                                    |

A new feature, *Suggested Claim Title*, is defined according to these
requirements:

1.  The Suggested Claim Title (the Suggestion) is text that User might want to
    use to replace the Claim's current title.

2.  The Suggestion will appear in two places:

    1.  On the Claim page, below the below the Claim title and above the
        creation date.

    2.  On the Claim Edit page, below the Description input.

3.  The Suggestion will have subtle styling, so to not be visually
    overly-dominant.

4.  - The Suggestion will have an arrow next to it, which, when clicked, will
      replace the Claim's title with the Suggestion.

    - The arrow will show this text on hover:
      > Replace the title with “\<the Suggestion>”.

    - The arrow will point upwards, pointing towards the Claim title (on the
      Claim page) or the Dsecription input (on the Claim Edit page).

5.  - The Suggestion will be based on the Claim's other fields.

    - The mapping of the Claim's other fields to the Suggestion will be
      user-defined, but with a useful default definition.

    - The default definition for the Suggestion will be:
      “\<Claim Provider>; \<Invoice Number>; \<Expense Date>” (not including the
      angle brackets; they are just to delimit the field names).

6.  - Users will be able to change the Suggestion definition on their Profile
      page, using a *Definition Builder*.

    - The Definition Builder will feature a text input plus a list of clickable
      field names.

    - Users will be able to click on each field name into the text input to add
      that field name into the Suggestion definition.

    - The Description field will be excluded from the list of available
      draggable field names.

