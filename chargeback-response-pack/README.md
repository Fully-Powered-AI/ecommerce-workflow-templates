# Chargeback response pack

Match a card dispute to its order, see which evidence is found or missing, and get a drafted response and the month's dispute ratio. A person decides.

> [!TIP]
> **Missing a template that is not listed here, or want these customized for your organization? Reach out to us.** This is a template, made to be customized and deployed. FullyPowered AI customizes and builds AI workflows, connects them to your business systems, installs them in your agents and puts them in the hands of the people who own the work. [See Chargeback response pack on our website](https://fullypowered.ai/workflows/chargeback-response-pack/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack). Not sure where to start? Email hello@fullypowered.ai and a person will answer.

**Quick start**

1. Read EXAMPLE.md to see what a good result looks like.
2. Copy all of TEMPLATE.md into your assistant, then give it your own inputs, or the invented ones from EXAMPLE.md.
3. Read what comes back. It marks what it checked and what is left for you.

*Workflow template · E-commerce and retail · Finance and accounting · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/chargeback-response-pack/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack)*

## The outcome

A dispute stops being a scramble through the order system, the carrier's site and the support inbox. The pack puts the processor's reason next to the order it concerns and says, item by item, what a bank expects to see for that kind of dispute and whether you have it. A delivery scan, a customer email, a policy page: each is either on the list with where it came from, or named as missing with where to get it.

The response is already written, in plain factual sentences, each pointing to the document that shows it. It says only what your records show and accuses nobody. A submit-by date a few days before the processor's deadline leaves time to chase anything missing.

You also see where the store stands: how many disputes were opened that month against how many card payments, set against your warning level and your processor's limit, and which other disputes are still waiting for an answer.

The owner decides whether to contest or accept, and a person submits through the processor. The AI assistant submits nothing, accepts nothing, refunds nothing and writes to no one.

## Who starts the work, and when

The finance lead, the bookkeeper or whoever runs the store's payments starts it the day the processor reports a new dispute or an inquiry. It runs again if missing evidence arrives before the submit-by date.

It is for disputes raised through the customer's bank. A customer who writes to the store asking for money back is a complaint, handled under your refund policy by [complaint and refund request handling](https://fullypowered.ai/workflows/complaint-and-refund-request-handling/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack).

## What they supply

- **The dispute notice,** copied from the processor's dispute page or email.
- **An order export** with the disputed order and the customer's earlier orders.
- **The carrier's tracking record** for the shipment.
- **Any messages** with the customer about the order.
- **Your policies** that applied on the order date: shipping, returns and refunds, cancellation.
- **Your disputes log,** and the number of card payments that month from the processor's report.
- **Your settings:** who decides and who submits, how many days of margin you want before the deadline, and your warning level and your processor's limit for the dispute ratio.

## What comes out

1. **The dispute and the order,** matched, with the amount checked against what was paid and any refund.
2. **The evidence list** for the dispute's reason, each item found, missing or not available, with a count.
3. **The customer's history:** earlier orders, whether any were disputed, and which details match.
4. **The facts for the decision:** what is at stake, what is missing, any flags, and a plain statement that the choice is yours.
5. **A draft response** with its numbered exhibits, and the items to add if they arrive in time.
6. **The month's dispute ratio** and the other disputes waiting for an answer.
7. **A coverage note** on what was read, what was missing and what could not be confirmed.

A good pack lets the owner decide and submit in one sitting, checking each sentence of the response against the exhibit beside it.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Finance and accounting](https://fullypowered.ai/functions/finance-and-accounting/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack): a dispute takes the money back out of the account, adds a fee, and every one counts toward the ratio the processor watches.
- [Customer support and service](https://fullypowered.ai/functions/customer-support-and-service/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack): the messages the team exchanged with the customer are often the strongest evidence in the pack.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack): card payments taken online and parcels left at the door are where these disputes begin.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack): a brand selling direct answers its own disputes, with no retailer in between.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack): when order volume grows past the point where the owner remembers every customer, and the deadline is easy to miss.

## What has to change for your company

Name who prepares the pack, who decides and who submits, and whether larger disputes always go to the owner. Choose your margin before the processor's deadline. Take the dispute ratio limit from your processor's terms, set your own warning level below it, and check both each year, since card network programmes change. Adjust the evidence lists to the way you sell: customer accounts add a login record; digital goods add proof of download. If your order export uses different column headings from the defaults, name them. It is written to run in ChatGPT, Claude, Copilot or Gemini from files and text you supply, and needs no connection to your store, processor or carrier.

## What has been checked

FullyPowered AI wrote this workflow template in its own words, drawing on a published chargeback method that is credited with it. It was editorially reviewed on 10 November 2026. It was tried on its invented example on 10 November 2026 in three runs: the template and example were revised after the first, and the third, a blind run on the current version, gave the same figures, evidence count, flags and ratio as the example; the record is published with it. It has not yet been tested in a client environment, and it has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a few past disputes whose outcome you already know, with hard cases written in advance: an export whose headings differ, a dispute already answered, a deadline two days away, a reason that could fit two kinds of dispute. The owner checks every sentence of the response against its exhibit before anything is submitted. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack) builds that test set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack) describes the record we keep.

- Written by FullyPowered AI.
- Sources and rights reviewed.
- Editorially reviewed on 10 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 10 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete workflow template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example with invented data.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the workflow template drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related workflow templates

- [Complaint and refund request handling](https://fullypowered.ai/workflows/complaint-and-refund-request-handling/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack)
- [Store facts file](../store-facts-file/)
- [Bank reconciliation preparation](https://fullypowered.ai/workflows/bank-reconciliation-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack)

## Make it yours

This workflow template is an example and a starting point. FullyPowered AI adapts it to how your company works, proves it on real work and rolls it out to the roles that use it. We can also build any other workflow for your company, including one that runs several steps, in a Workflow Sprint or a scoped implementation. [Talk with us](https://fullypowered.ai/contact/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=ecommerce-chargeback-response-pack&from=gh-ecommerce-chargeback-response-pack).
