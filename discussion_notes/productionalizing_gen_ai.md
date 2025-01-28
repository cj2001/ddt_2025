# Navigating the Challenges of Deploying Generative AI in the Real World

These notes are from the informal Sunday discussion I led at Data Day Texas, 2025. The session was a chance for attendees to ask questions and share their experiences with freelancing in the data science field.  All comments were off the record, and I have anonymized the content to protect the privacy of the participants.

In order to determine subjects to discuss, the participants were polled for topics and then up/down voted with those getting the highest votes being discussed.

### Key Takeaways

- Data quality: LLMs are giving bad output based on the poor data quality going in.
- LLMs on top of structured data
  - Discussion of use cases, including writing faster SQL and real-time event processing.
- Definition of "garbage in/garbage out" depends on the context
- How to evaluate the quality of LLM output?  There was a bias for human evaluation and not allowing LLMs to do too much judging.
- Guardrails need to be updated when the model is updated
  - Consider adversarial attacks as the basis for updating guardrails
- Discussion on the existing tooling and opportunities for AIOps
  - Models are changing so fast, how to keep the pipelines updated?
  - DOK, SailPlane, and NVidia NIMs called out as solutions
- Fine tuning and RAGs
  - Most participants were not involved in fine tuning
  - Even if a RAG is 100 percent accurate, the LLM isn't
- Modalities that are not presently being addressed by LLMs
  - Cameras on users responding to their gestures
  - It is hard to describe certain things via text
    - Spatial awareness
    - example: "describe purple"
  - Understanding emotion in audio or video
