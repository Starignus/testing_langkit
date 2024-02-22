# Testing Langkit

* [WhyLogs](https://whylogs.readthedocs.io/en/latest/examples/experimental/whylogs_UDF_examples.html?highlight=udf#Logging) Telemetry for the ML stack: It is an open-source tool for profiling your data and creating Telemetry about production systems at scale at massive scale. So this is an open-source tool for doing that Telemetry collection and summarization. 

* [LangKit](https://github.com/whylabs/langkit/blob/main/langkit/docs/modules.md#pii) Observability and security for LLMs: It is an open-source tool that is built on top of Whylogs, specifically with metrics for hallucinations data, Quality Security, sentiment, governments of language models.

* [WhyLabs aI Observatory](https://whylabs.ai/) Monitoring and actionable production workflows that use the two products on top for monitoring.

For some exercises, you might need to send LangKit profiles to WhyLabs. We will need three pieces of information:
* API token
* Organization ID
* Dataset ID (or model-id)

You can [sign in](https://whylabs.ai/free) and grab a free account to obtain those. You can create the next when required: 

* Create a new project and note its ID (if it's a model project, it will look like model-xxxx)
* Create an API token from the "Access Tokens" tab
* Copy your org ID from the same "Access Tokens" tab

You can see the video for the first notebook at [46:00 min](https://www.youtube.com/live/DLJ8m3wMJrs?si=-GQFX_xd6OZRevkh&t=2713) where the setup of your dashboard where you will send LangKit profiles.

As part of exploring LangKit capabilities, [the next issue was raised](https://github.com/whylabs/langkit/issues/230).
