Adapted from the [MongoDB Documentation Style Guide](https://docs.mongodb.com/meta/)

# Writing Guidelines

[Use Active Voice](writing-guidelines/use-active-voice.md)

[When Do You Use Passive Voice?](writing-guidelines/when-do-you-use-passive-voice.md)

[Use Present Tense](writing-guidelines/use-present-tense.md)

[Write to the User](writing-guidelines/write-to-the-user.md)

[Restrict Sentence Length](writing-guidelines/restrict-sentence-length.md)

[Create Short Paragraphs](writing-guidelines/create-short-paragraphs.md)

[Limit Using Be as the Main Verb](writing-guidelines/limit-using-be-as-the-main-verb.md)

[Use Active Verbs](writing-guidelines/use-active-verbs.md)

[Avoid Verbs Built from Nouns](writing-guidelines/avoid-verbs-built-from-nouns.md)

[Use the Simplest Tense](writing-guidelines/use-the-simplest-tense.md)

[Use Gender-Neutral Pronouns](writing-guidelines/use-gender-neutral-pronouns.md)

## Use Gender-Neutral Pronouns

Use gender-neutral pronouns unless you are referring to a specific individual. 

| Use | Avoid |
| --- | --- |
| They, their, theirs, them, or themselves as a singular pronoun. | he, him, his, she, or her as gender-neutral pronouns and he/she or (s)he or other such punctuational approaches. |

Following are some examples:

- Tell the next caller they need to forward the status.
- Every account manager should thank their customer.
- Who left their laptop opened and unsecured?
<br/>

## Use Positive Statements

Positive statements are easier to understand than negative statements and are typically easier to understand.

| Use | Avoid |
| --- | --- |
| The software works properly when installed correctly. | The software won’t work properly unless you install it correctly. |
| Remember to involve your business users in the scheduling process. | Don’t forget to involve your business users in the scheduling process. |
| Sometimes you want to prevent a search engine from indexing a website. | It isn’t uncommon in certain situations to not want to allow indexing of a site by a search engine. |

## Avoid Negative Words

Try to avoid the following negative words, using instead the suggested alternatives. However, always be honest and transparent about issues.

| Avoid | Alternative |
| --- | --- |
| damage | affect |
| catastrophic | serious |
| bad | Use serious or add an explanation |
| fail | unable to |
| kill | cancel |
| fatal | serious |
| destroy | remove |
| wrong	| incorrect, inconsistent |

## Use Correct Punctuation

When you use correct punctuation, you help users understand the content the first time they read it. Following are a few basic guidelines to apply:
- Use a period at the end of sentences, even imperative ones (such as steps).
- Use a comma before the last item in a series (known as the serial comma).
- Use a comma to separate independent clauses, and include a coordinating conjunction (such as and).
- Avoid using semicolons. You can almost always use a period in the place of a semicolon.
- Don’t use a slash (/) to present a choice among, or a series of, actions or objects. Rewrite the phrase to eliminate the slash mark. = - Exceptions are established terms like client/server and read/write.
- Avoid using exclamation points, question marks, ellipses, or single quotation marks in regular text. Although these punctuation marks might appear in code elements, messages, literal commands, or UIs, they’re rarely useful when writing descriptions or instructions for users. One exception is the use of question marks in FAQ topics.
<br/>

## Write for Accessibility

Writing with accessibility in mind improves the documentation experience for all our users.
- Avoid unnecessary font formatting. (Screen readers explicitly describe text modifications.)
- Don’t force line breaks (hard returns) within sentences and paragraphs. Line breaks might not work well in resized windows or with enlarged text.
- Avoid camel case (camelCase) and all caps (ALLCAPS). Some screen readers read capitalized letters individually. Some languages are unicameral; they don’t have lower and upper cases.
- Depending on the screen reader (or personal settings), not all punctuation marks are read. Make sure the same meaning is conveyed to the reader without punctuation marks. For that reason, avoid the use of exclamation marks, question marks, and semicolons.
- Don’t use & instead of and in headings, text, navigation, or tables of contents; however, it’s OK to use & when referencing UI elements that use &, or in table headings and diagram labels where space constraints require abbreviation. And of course it’s fine to use & for technical purposes in code.

### Provide Context for UI Elements

Don’t identify UI elements using only one sensory characteristic (such as color or location).

Directional phrases like “at the top of the page” or “right-hand side” might not provide adequate information to someone using a screen reader. Even relating one element to another with phrases like “next to” or “above” might not provide the correct context.

- When referring to a UI element in a procedure, use previous steps to clearly navigate the user to the element to maintain clarity and avoid wordiness. If the same icon, button, or element appears on the page more than once, be more descriptive by using section, modal, or panel headings and field names.
- If a UI element is hard to find, provide a screenshot.
- Use the label of an element and not its shape or color to describe it.

| Use | Avoid |
| --- | --- |
| Click Save. | Click the green button. Click the round button. |

### Write for Ease of Reading

- Break up walls of text to aid in scannability. For example, separate paragraphs, create headings, and use lists.
- Use shorter sentences. Try to use fewer than 26 words per sentence.
- Define acronyms and abbreviations on first usage and if they’re used infrequently.
- Use parallel writing structures for similar things. For example, start each list in the same format.
- Place distinguishing and important information of a paragraph in the first sentence to aid in scannability.

### Use Descriptive, Hierarchical Headings

Users of screen readers often scan a page by jumping from heading to heading. Make the hierarchy clear and headings meaningful.
- Use descriptive headings and titles because they help a user navigate their browser and the page. It’s easier to jump between pages and sections of a page if the headings and titles are unique.
- Use a heading hierarchy and don’t skip levels. For example, put an h3 only under an h2.
- Don’t use a heading level that doesn’t fit the hierarchy. Find another way to change the visual formatting of a heading.
- Don’t have empty headings or headings with no associated content.
- Format headings using RST markup, like heading types, not bold.
- Use an h1 for the page title or main content heading.

### Use Meaningful Link Text and Formatting

Some people who use screen readers jump from link to link to scan a page and need to understand what a link contains.

Use meaningful link text. Links should make sense when read out of context.
Don’t use click here or read this document. These phrases provide no information about what a link contains.
Use an external link icon to indicate that the link opens in a new window or tab.
Avoid adjacent links or put a character in between to separate them.
If a link downloads a file, the link text must indicate this action as well as the file type.

### Use Alternative Text for Images

Screen readers read alternative text aloud so that users can better understand an on-page image.

- Provide alternative (alt) text that adequately summarizes the intent of each image. Don’t describe the image in detail.
- Don’t present new information in images; always provide an equivalent text explanation with the image.
- Don’t repeat images unless absolutely necessary.
- Don’t use images of text, code samples, or terminal output. Use actual text.
- Use SVG instead of PNG if available. SVGs stay sharp when you zoom in on the image.

### Caption Videos, Recordings, and GIFs
- Provide captions, transcripts, or descriptions of audio and video content. For example, you can use the autocaption feature in YouTube. - Make sure that captions can be translated into major languages.
- Avoid flickering or flashing elements. They can cause anything from motion sickness to a seizure.

### Use Simple Tables
- Don’t use tables unless it’s the best method to present your information. Tables are challenging for screen readers. If you must use a table, use a simple table that doesn’t have cells that span columns or rows.
- Avoid tables in the middle of a numbered procedure.

### Format a Page for All Abilities

Make sure that your document conveys all the information you intended if you view it in the following contexts:
- Without sound
- Using only sound
- Without color
- Using a keyboard
- With screen magnification
- Without punctuation
- Don’t use color, size, location, or other visual cues as the primary way of communicating information.

If you’re using color, icon, or outline thickness to convey state, then also provide a secondary cue, such as a change in the text label.


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

