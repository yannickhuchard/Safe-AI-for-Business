![Banner Image Alt Text](safe_ai_guidelines_for_business.png)


# <div align="center">Safe AI Guidelines for Business</div>
Safe AI Guidelines for Business – an open-source initiative designed to empower businesses and nonprofits to adopt AI to innovate responsibly. The goal is to kickstart the enterprise journey towards AI, with resources built to share, adapt, and thrive.

&nbsp;


##Introduction

The purpose of this document is to provide a generic framework for the usage of AI technologies, such as ChatGPT, Claude, Dall-E, Midjourney, Bing, Bard, D-ID, which either generate content or transform it using human knowledge and identities throughout Text, Images, Videos, Audio, and other forms of intellectual property.

As AI advances in complexity and the benefits it provides, as well as the potential impact it may have on each and every business, the goal is not to forbid these companies but rather to push for public debate followed by a public contribution to a global asset of humankind.

The following is a proposal for guiding companies and other organizations, such as schools, in having safe and risk-limited usage of AI:

We seek benefits that are not only for your enterprise but also for humankind, which are:
- Establishing a baseline rulebook, instructions, and explanations for your organization.
- Creating foundational guidelines as a means of protection and responsible behavior by design.
- Establishing a tacit agreement by publicly announcing the conscious and responsible usage of AI.
- Making this open source with open contribution, which gives the opportunity to make these guidelines better over time and also provide the means to make it available in several languages.

##Context:
- ChatGPT uses reinforcement learning, which is a feedback loop with user ratings and your content. Your content may be used for training the next GPT model.
- ChatGPT is free. When it is free, you are the product. However, it is a fair trade: attention, interactions, and feedback for free intelligence and digital skills.
- Be aware that these technologies use human knowledge as a starting point, but they may also be fed with AI-generated knowledge to kickstart the creation of a new model, including for research purposes. Hence, your information may already be mixed in another dataset, but also the "truth" or "factual knowledge" might have been altered.
- Your data may be shared unintentionally or intentionally in the future and be part of an AI model. AI companies may freely use samples according to certain use cases, or as a result of an internal error, given the free nature of the service.
  - Using the "vote" button will send a signal to the AI system that the response is satisfactory or unsatisfactory. In some cases, you are invited to share more descriptive feedback. This complements the AI training system by providing additional data with supplementary contextual data and metadata. Thus, your data, including elements such as session information, identifiers, browser information, etc., may be shared with the platform. RLHF is not suitable for use in a business environment.
  - Other systems or plugins, for instance, https://sharegpt.com/, actively invite you to share your interactions to crowdsource your prompts, AI model responses, and your interactions. These are not suitable for use in a business environment unless the system is internal to your company AND its usage is explicitly governed.
- Any data that is leaked resulting from hacking or unintentional storage of data in an unsecured location may be exploited by an AI or incorporated into an AI model.
- Companies hosting AI models as a service are subject to different regulatory systems which may not be compatible with those of your country. For example, OpenAI is an American registered company, so using its services has risks that you must assess and mitigate as a business, under considerations such as SCHREMS II.
- There are other regulations you must consider, such as GDPR in the Eurozone and the NIS directive to guarantee the protection of your network.
- The following provides foundational guidelines, but you must assess the risks pertaining to your industry and regulatory scope.

##Consider:
- Human-to-human interaction
- Human-to-machine interaction
- Human-to-fleet interaction
- Human-to-organization interaction
- Organization-to-organization interaction
- Machine automation and autonomy
- In particular, consider those more susceptible to influence, such as children and the elderly.

##AI Models and Technologies
(Guideline: Adjust the Allow/Deny rules according to your business strategy, your corporate policies and regulatory scope)

####Allowed AI Systems and Their Usage:

| Allow                                         | Usage                                                    |
|-----------------------------------------------|----------------------------------------------------------|
| ChatGPT                                       | Review, generation, feedback, complementation, transformation |
| GPT API                                       |                                                          |
| Claude.ai                                     | Review, generation, feedback, complementation, transformation                                                         |
| Dall-E 2                                      |                                                          |
| Adobe Firefly                                 | Content Marketing (internal only)                                                         |
| ElevenLabs                                    |                                                          |
| Jasper.ai                                     |                                                          |
| Canvas                                        |                                                          |
| LLaMa 2                                       |                                                          |
| Mistral                                       |                                                          |
| Palm                                          |                                                          |
| GPT-4LL                                       |                                                          |
| AI Infrastructure: Langchain, LlamaIndex      |                                                          |
| Etc. Add your company's approved AI systems to the list. | |


####Denied AI Systems and Their Usage:

| Deny                                                     | Usage |
|----------------------------------------------------------|-------|
| Unauthorized, harmful, hateful, or dangerous models      | ALL   |
| GPT-4chan                                                | ALL   |
| GPTChaos                                                 | ALL   |
| ...                                                      | N/A   |


Note: For AI consumed as a service, it is recommended to implement:
- Proxy URL whitelisting with RBAC, giving access to online service AIaaS. This prevents employees from being tempted to use their personal accounts or free tiers.
- Default use of enterprise licenses.
- User license-based allocation for auditability and analytics.

##Guidelines DATA:
- Do not add customer data to external Generative AI systems.
- Do not add employee data without explicit consent and the legal right to process them.
- Utilize "privacy mode" in ChatGPT or any similar functions that ensure user privacy and data privacy.
- In general, avoid using Personal Information.
- Do not add content or data subject to proprietary intellectual property (yours or someone else's).
- Avoid injecting generated data into real data if ultimately the data mirrors reality. This act is considered tampering.
- Do not train the model with data that you do not own or data that is subject to intellectual property rights.
- If generated data is mixed with real data that leads to decision-making, explicitly specify each part of the process where AI is used and note that the outcome contains elements of generated AI.
- Consider using watermarks for AI-generated content if you believe it is your duty to inform or educate your audience. This decision should be guided by your ethics policies and the context in which AI is used to convey your message or advertisement/promotional content.

##Trust:
- Engage in brief interactions with a human when dealing with the outcomes of AI-generated content, assets, and code.
- Always test AI-generated code.
- Avoid relying exclusively on AI for processes and mechanisms at strategic decision points (e.g., hiring, firing, acquisitions, technology investments, human team management, etc.).
- Refrain from data washing, where data would have been unethically or illegally collected, then used to create generative AI models that produce an entirely new dataset from the knowledge contained in the model.

##Legal and Compliance:
- If your customer data is processed by ChatGPT or another service, the general terms and conditions and the data privacy policy must explicitly state the usage of these services.
- Document the processes involving your AI systems so regulatory authorities can verify that your model creation and exploitation are performed in a safe, fair, and responsible manner, providing ethical assurance to your consumers.

##Governance:
- Utilize these safe AI Guidelines to define the scope of usage, engineering, operations, and supervision in your company.
- Assess the introduction of a system powered by AI properly:
  - Determine the type of AI capabilities contained in the system: generative, discriminative, predictive, decision-making, transformative.
  - Evaluate intelligent functions: classifications, recognition, review.
  - Consider if the AI is tasked with making decisions on critical activities:
    - If yes, determine what explanatory measures are in place to clarify and certify the AI decisions.
    - If yes, identify what mechanisms are in place to ensure the AI decision's consistency, coherence, and bias reduction.
- Establish an AI Enterprise registry, listing AI models, AI-powered systems, and their uses.
- Ensure these systems are registered in the CMDB.
- Verify that Enterprise Architecture ensures the Enterprise Architecture repository indexes these systems or that there are dedicated enterprise architecture views.
- Maintain control over new model versions. It is expected that each new model version improves upon the previous one. Nonetheless, the Enterprise must remain in control and establish mechanisms for controlling the risks inherent to the new model (anti-regression, exaggeration, etc.).

##Security:
- Never write down passwords.
- Use a proxy with a data leakage protection system.
- Do not use any AI model as a Service system without encrypted connectivity (HTTPS, FTPS, SSH, etc.).

##Risk:
- Mitigate the risk of losing personalization.
- Prevent the production of content without human supervision.
- Avoid producing content without human verification.
- Guard against producing content that could lead to brand damage.
- Prevent hijacked usage of AI chatbots for purposes other than intended.
- Avoid AI jailbreak scenarios.
- Protect against data breaches due to access to unauthorized data.
- Prevent data breaches due to personal data being used in the training dataset.
- Ensure AI-driven decisions can be explained.
- Verify that AI-driven decisions can be verified.
- Reduce the risk of content being used by an employee to harm or bully the company or an employee/contractor.

##Ethics:
- Prohibit Not safe for work (NSFW) prompts.
- Do not use AI external to your company to probe or analyze the weaknesses of your internal systems unless you are a professional ethical hacker explicitly missioned to do so.
- Do not use the image of someone (except yourself) as input for generating an alternate situation without explicit consent.
- Do not use the voice of someone else without explicit consent.
- When AI-generated content is used to explain a fact, add the label "generated by AI" explicitly.
- Avoid deep fake generation of any kind.
- Refrain from publishing false, intentionally biased, or half-truths, or from withholding information to induce erroneous or incorrect perceptions.
- If AI is used for statistical means, generate samples first to identify where the bias of the model lies (gender, origins, classifications, segmentation, selections, etc.).
- Avoid using content that may be close to/perceived as religious content.
- Do not use AI for any form of social engineering, psyops, or behavioral diagnostics upon an individual unless it is with explicit and verifiable intent to help the individual and your job function or relationship with the person provides a legitimate purpose.

##Environmental, Social, and Corporate Governance (ESG):
- The models used should conform to your ESG criteria.

##IT Security AI attack vectors and vulnerabilities you must protect against:**
- Prompt Injection
- Poisoning of data training sets for decision-making hijacking
- Poisoning of data training sets for bias manipulation
- Poisoning of data training sets for intentional data obfuscation
- Man-in-the-middle attacks in the LLM chain infrastructure
- Brute force Reinforcement Learning with Human Feedback exploitation
- Inappropriate behavior by Roleplay and Impersonation
- Credential leakage from Retrieval Augmentation Generation


##AI Policy:
- It is essential to articulate a clear and comprehensive AI policy that outlines your company's stance on the use of AI technologies. This policy should align with the ethical guidelines, legal requirements, and industry best practices, ensuring responsible and transparent AI use within your company's operations.
- AI Policy Template: [AI Enterprise Policy](AI-Corporate-Policy.md)


##Transition to a Safe AI-Enabled Enterprise:**
- Your CTO, CIO, or Chief Scientist should define an AI Strategy in collaboration with the Chief Risk Officer, the Data Protection Officer and the Corporate Audit Services.
- Helper: [AI Strategy Tool](https://amase.io/amase-ai-strategy-tool/ai_strategy_tool.html)
- This Strategy should be safeguarded and augmented by this Safe AI Guideline framework, tailored for your enterprise.
- Once the Safe AI Guidelines are published as a policy:
  - Train your staff in adopting these AI Guidelines in the context of the AI Strategy or the IT Strategy. Pair this with training about AI risks and the potential for loss of expertise if AI is used improperly.
  - It is highly recommended to provide Prompt Engineering training to your staff so that each can benefit to the fullest from LLM-Based Models and develop AI piloting skills, which ultimately trigger self-augmentation, company's augmentation, and increase individual productivity.
  - Establish a compliance framework.
  - Have Corporate Audit Services to:
    - Audit IT systems that are AI-powered.
    - Verify the data pipeline according to Data Privacy Principles, Incorrect/Bias data/Data influencing the algorithm.
    - Review the decision points made by an AI system.
    - Examine the occurrences of AI augmentation.
    - Assess the impact from an ethical human resources point of view where AI systems cause total job displacement without offering an alternative role in the same company (for example, full-time procedure writers should be offered. Ultimately, we decide that AI should assist humans in collaborating in a human environment, with the acceptance that some tasks may be undertaken by AI/robots, instead of opting for a path where AI replaces the human).

##Recommended Usage:
- Data mapping
- Data transformation
- Test data generation
- Data verification
- Data explanation
- Generating media (images, music, videos, 3D assets)
- Language translation
- Synthetic Data generation
- Transcription
- Sensorial detection (visual, auditory, infra-red, seismic, etc.)

##Consequences:
- Organizations must have explicit rules, formalized in the Code of Conduct, and signed by each worker and student so that they are explicitly linked to the employment contract, service contract, and student.
- The organizations should have an explicit paragraph in their IT charter defining the boundaries of AI usage.
- The Data Office should have explicit AI guidelines and data usage guidelines in the perspective of AI models engineering and model usages.

##Governing Regulations:
- GDPR
- Consider the AI regulatory frameworks pertaining to geographical regions like the EU AI Act or the US AI Strategy Framework.

### Useful links
- [EU AI Act - Draft](https://www.europarl.europa.eu/doceo/document/TA-9-2023-0236_EN.pdf)
- [EU AI Strategy](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=COM:2018:237:FIN)
- [US White House's Executive Order on the Safe, Secure, and Trustworthy Development and Use of Artificial Intelligence](https://www.whitehouse.gov/briefing-room/presidential-actions/2023/10/30/executive-order-on-the-safe-secure-and-trustworthy-development-and-use-of-artificial-intelligence/)
- [Canada's AI and Data Act](https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document)
- [AI Risks - Centre for AI Safety](https://www.safe.ai/ai-risk)
- [OECD AI Principles](https://oecd.ai/en/ai-principles)





