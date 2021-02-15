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

### When Do You Use Passive Voice?

You can use passive voice when using active voice will create one of the following problems:
- Sounds like you’re blaming the user. For example, you can use passive voice in an error message or troubleshooting content when the active subject is the user.
- Makes the sentence wordy or awkward.
- Would emphasize the performer when you don’t know the performer of action or you want to de-emphasize the performer in favor the object on which the action is performed.

| Acceptable (passive) | Avoid (active) | Why? |
| --- | --- | --- |
| A flag was set incorrectly. | You set the flag incorrectly. | The active voice blames the user. |
| Account owners can’t be assigned additional roles, and their access can’t be restricted. | Administrators can’t assign account owners additional roles, and they can’t restrict the access of account owners. | In this context, the object, account owners, is more important than the actor, administrators. |

## Use Present Tense

Users read content to learn how to perform tasks or to gather information. These activities occur in the users’ present time. This makes the present tense appropriate in most cases. The present tense implies that users should take action now. Sentences that use the present tense are easier to read than sentences that use past or future tense.

## Write to the User

Users are more engaged with content when it talks to them directly. Use second person to talk to users directly, addressing the user as you. Second person promotes a friendly tone. 

Use second person with the imperative mood (in which the subject you is understood) and active voice to eliminate wordiness and confusion about who or what initiates an action, especially in procedural steps.

Examples:
- Use the following configuration if you want to enable authentication.
- Enter your access keys.
- Install and configure the AWS Command Line Inerface. (imperative)

## Write Clear and Concise Sentences and Paragraphs

## Use Active Verbs

Verbs carry the action in a sentence. Use active verbs rather than verbs like *be*, *have*, *make*, or *do* (and their variants). 

Avoid gerunds (-ing words) and nominalizations (making nouns from verbs) make the nouns carry the action and weaken the meaning. Replace weak verbs and gerunds with strong, action-oriented verbs to restore focus to verbs from nouns.

| Active Verb |	Weaker |
| --- | --- |
| Role-Based Access Control (RBAC) restricts service access to authorized users. | Role-Based Access Control (RBAC) is a method of restricting service access to authorized users. |
| If the node can’t access the Internet, the installation process fails. | If the node doesn’t have Internet access, the installation process fails. |
| To create a server, specify a name, flavor, and image. | You create a server by specifying a name, flavor, and image. |
| When you create a server, … | When creating a server, … |
	
### Avoid Verbs Built from Nouns
Many nouns are built from verbs, for example, description and explanation. Such nouns are called nominalizations. Use active verbs instead.

| Active Verb | Nominalization |
| --- | --- |
| The following table describes each of the products. |	The following table provides a description of each of these products. |
| Install the product by completing the following tasks. | Perform the installation of the product by completing the following tasks. |
| The program encrypts user IDs and passwords. | The program enables the encryption of user IDs and passwords. |

### Use the Simplest Tense

| Simplest | More Complex |
| --- | --- |
| Before you perform this task, complete the prerequisites. |	Before you perform this task, you should have completed the prerequisites. |
| To start, three ports are open: ssh, http, and https.	| To start, you are going to have three ports open: ssh, http, and https. |
| If you use a Red Hat distribution, iptables works a little differently. | If you are using a Red Hat distribution, iptables work a little differently. |


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

