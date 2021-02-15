Adapted from the [MongoDB Documentation Style Guide](https://docs.mongodb.com/meta/)

# Writing Guidelines

## Use Active Voice

*Active voice* makes the performer of the action (usually the reader or user) the subject of the sentence.

*Passive voice* makes the recipient of the action (not the performer) the subject of the sentence.

When compared to passive-voice sentences, active-voice sentences are:
- more engaging
- less complicated
- less wordy
- easier to understand

With active voice, you can distinguish the actions and responses of the user from those of the technology.

### Example

Beginning users look for specific calls to action in step-by-step content. Active voice makes this clear. Consider if you write a step that reads “The service can be restarted.” As written, this sentence reads as a consideration or a possibility, not an instruction. If the user skips this step due to this confusion, the rest of the tutorial might fail. If you write “Restart the service”, you remove all doubt. This also clarifies that the user restarts the service.

| Use (active) | Avoid (passive) |
| --- | --- |
| After you install the software, start the computer. | After the software has been installed, the computer can be started. |
| Click OK to save the configuration. | The configuration is saved when the OK button is clicked. |
| Create a server. | A server is created by you. |
<br/>


### When Do You Use Passive Voice?

You can use passive voice when using active voice will create one of the following problems:
- Sounds like you’re blaming the user. For example, you can use passive voice in an error message or troubleshooting content when the active subject is the user.
- Makes the sentence wordy or awkward.
- Would emphasize the performer when you don’t know the performer of action or you want to de-emphasize the performer in favor the object on which the action is performed.

| Acceptable (passive) | Avoid (active) | Why? |
| --- | --- | --- |
| A flag was set incorrectly. | You set the flag incorrectly. | The active voice blames the user. |
| Account owners can’t be assigned additional roles, and their access can’t be restricted. | Administrators can’t assign account owners additional roles, and they can’t restrict the access of account owners. | In this context, the object, account owners, is more important than the actor, administrators. |

## Use Active Voice

### Why Use Active Voice

## Use Present Tense

## Use Second Person and Imperative Mood

## Write Clear and Concise Sentences and Paragraphs

## Use Effective Verbs

## Clarify Gerunds and Participles

## Clarify Ambiguous Modifiers

## Use that, which, and such as Correctly

## Clarify Pronouns and Antecedents

## User Gender-Neutral Pronouns

## Use Positive Statements

## Use Correct Punctuation

## Use Interjections with Care

## Write for Accessibility

## Write for a Global Audience

# Style Guidelines

## Titles and Headings

### Semantics
- Create succinct, meaningful, descriptive titles and headings, and place the most important words first.
- Create titles that clearly describe what the page is about for a user who is unfamiliar with the product. E.g., use “Hyperparameter tuning” instead of “Katib.”
- Create titles that don’t rely on body text or other titles for their meaning (that are, in other words, independent of context). Users should be able to tell from a title whether the information in the article is relevant to their needs. Avoid ambiguous one-word titles, such as “Overview.” - E.g., “Submit Kubernetes resources from a Jupyter notebook” instead of “Submit Kubernetes Resources.” This is important for SEO and for readability in search results. It also bulletproofs against introducing a confusing experience if a page is reorganized into a different section for some reason.
- Ensure that each title and heading is unique within a given content set.

### Capitalization
- Use headline-style capitalization for most titles and headings, including article, chapter, table, figure, and example titles, as well as section and procedure headings. Headline-style capitalization uses initial uppercase letters for the first, last, and all the significant words in the title. Capitalize all words in the title except for the following types of words:
  - Articles (a, an, the) unless the article is the first word in the title or follows a colon
  - Coordinating conjunctions (and, but, for, nor, or, yet, so) unless the conjunction is the first word in the title
  - Prepositions of any length, unless the preposition is the first or the last word in the title or is part of a verb phrase
  - The word to in an infinitive phrase unless to is the first word in the title
  - Second elements attached by hyphens to prefixes unless they’re proper nouns or proper adjectives
  - Words that always begin with a lowercase letter, such as literal command names or certain product or software names
- Use sentence-style capitalization for titles of steps in step files.

### Style and Structure
- Ensure page titles are the same wherever they are displayed. Do not shorten titles to make them fit a table of contents or navigation element.
- Include articles, prepositions, and punctuation as needed for clarity. However, avoid using an article (a, an, or the) as the first word.
- Avoid showing both an abbreviation and its spelled-out term in a title or heading. To help control the length of titles and headings, show the abbreviation in the title or heading and then define it in the first paragraph of the text.
- Don’t end a title or heading with a colon or period. If the title or heading is in the form of a question, end it with a question mark.
- Avoid having only a single heading at any level (for example, a single subsection in an article or section). If you find that you have a single heading at any one level, consider whether you can reorganize the information to either eliminate the heading or add a second one at that level.
- Avoid having more than two levels of sections within an article or topic. If you use more than two levels of sections, consider whether you can reorganize to make the structure flatter.
- Don’t “stack” titles or headings. That is, don’t immediately follow a title or heading with another title or heading. Text should always intervene between them. Ensure that such text is meaningful. If it is just filler text, consider whether you can restructure the content.
- Use a consistent grammatical structure for the titles and headings of specific types of content:

  | content | grammar | example |
  | --- | --- | --- |
  | conceptual | Any grammatical structure that's appropriate except a verb, gerund, or infinitive | Contribute to Kubeflow |
  | step-by-step instructions | An imperative verb | Install Kubeflow |
  | tutorial or high-level process | A gerund | Managing an EKS Cluster |
  | reference | A plural noun or noun phrase | Kubeflow Versioning Policies |

