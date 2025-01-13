# Google Prompting Essentials

Some popular delimiters include:

- **Triple quotes ("""):**
  These create a distinction between the different elements of the prompt, like your task and context.
  They’re useful for when you want to clearly separate text within a prompt to signify different meanings, purposes, or other distinguishers.

- **XML tags:**
  These are like labels that mark different sections of more complex prompts.
  For example, add “<task>” to make it super clear where your task begins and “</task>" to indicate where it ends.

- **Markdown tags:**
  These are symbols you can use in prompts to add formatting.
  For example, if you were to use a gen AI tool to copy-edit your work, you could surround text with “\_” to italicize it or “\*\*” to bold it.
  This preserves your formatting as you move it into a gen AI tool, which generally uses plain, or unformatted text.

### Generate better outputs through iteration

- **Revisit the prompting framework:**
  Make sure your prompt is clear about your desired task and includes a specific persona and format, plenty of context, and offers relevant references that help inform the output.

- **Break the prompt into shorter sentences:**
  Instead of packing everything into a complex and lengthy prompt, address each individual step in a separate prompt until you’ve accomplished everything.

- **Introduce constraints:**
  Focus the gen AI tool’s output by adding constraints, or limitations, to your prompt.
  When you set boundaries for specific categories, lengths, formats, or other details in your prompt,
  you help the tool provide a more precise output.
  It’s like asking for a list of food recipes but specifying that the recipe should only use seasonal ingredients and take less than 30 minutes to prepare.
  Adding constraints can actually encourage more inventive, targeted results that better match your needs.

- **Tweak your phrasing or switch to an analogous task:**
  Shift your language to explain what you mean in a different way.
  Or, try a different task that’s similar to what you’re trying to complete but different enough to trigger a new response.

### Strategies for data analysis

- **Text analysis:** Easily surface themes, determine tone, and classify key topics in text-based data. Have a few thousand open-ended responses from a community survey? Gen AI can help you quickly understand what’s most important to people, how they feel about the town’s proposed plans, and where the final initiative should make an impact.

- **Data augmentation:** Expand a limited dataset with simulated data to make it more robust. Say you work in fraud prevention. You want to analyze your company’s data about fraudulent purchases, but there are only a handful of data points. You can prompt a gen AI tool to generate new data from your current dataset to get a more comprehensive view of how fraud might happen and what to look out for. The key with data augmentation is to be transparent about what's real and what's augmented data, and the augmentation should be as realistic as possible. Augmentation can’t give you hard facts, only suggest trends.

- **Question and answering:** Get answers about your data in plain language, like whether your sales from last quarter were up or down. It’s like checking in with your colleague who compiled the information—just with fewer emails.

- **Scenario analysis:** By noticing patterns in past data, gen AI tools can make educated guesses about what might happen in the future. That means you can play out different scenarios to check what kind of impact they might have, like prompting to ask how a change in traffic patterns would impact your commuting time, or which days of the week your office space should expect the highest number of visitors.

- **Image and visual analysis:** Gen AI can help you quickly identify patterns and come to conclusions about your visual data without having to sift through stacks of images or watch hours of footage. You could even paste in a chart displaying your team’s sales figures for the past two years in your prompt, and ask questions about it for more focused analysis.

- **Customer and market research:** A gen AI tool can analyze surveys, social media, and other industry-specific data like charts and graphs to uncover what customers want and how your market is changing.

### Embedded AI tools

- **[Gemini in Google Sheets:](https://support.google.com/docs/answer/13951830?hl=en)** Create tables, establish formulas, and summarize Drive files or Gmail messages to organize and analyze your data directly in your spreadsheet.

- **[Tableau Pulse:](https://www.tableau.com/products/tableau-pulse)** Receive personalized, automated insights about your data as snapshots on the Tableau Cloud platform, or regular digests sent through Slack or email.

- **[Looker Studio:](https://cloud.google.com/looker-studio?hl=en)** Access a robust library of report templates, easily explore underlying data through prebuilt data connectors, and embed final reports into any web page or intranet to share your findings with the audience that needs them most.

- **[BigQuery data insights:](https://cloud.google.com/bigquery/docs/data-insights)** Uncover patterns, assess data quality, and perform statistical analysis by generating automated queries based on your information’s metadata.

### Prompt chaining

- **Chain-of-thought prompting** you can ask the tool to retrace its path from input to output, listing out the reasoning behind its response step by step.
- **Tree-of-thought prompting** Tree-of-thought prompting can help you compare many possible solutions at once and evaluate which will be most useful.

And in some cases, combining tree-of-thought with chain-of-thought can give your prompting the boost it needs.  
When you need insight on a tool’s reasoning and other options to take within that reasoning, the two techniques can work perfectly together.
