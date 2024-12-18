## CrewAI 
![3p-agentic-frameworks](assets/crewai-aws.png)

CrewAI, a Python-based open-source framework, simplifies the creation and management of multi-agent systems, enabling agents to work together seamlessly, tackling complex tasks through collaborative intelligence.

## CrewAI Official Documentation

**Docs:** https://docs.crewai.com/introduction 

## CrewAI + AWS Examples

### [AWS Infrastructure Security Audit Crew](examples/aws-security-audit)
A comprehensive example demonstrating how to use CrewAI agents to perform security audits of AWS infrastructure, analyze configurations, and generate detailed reports using Claude 3 Sonnet.

### Importing LLMs from Amazon Bedrock

**Model IDs Supported:** https://docs.aws.amazon.com/bedrock/latest/userguide/models-supported.html

**LLM Configuration:** 

```python
AWS_ACCESS_KEY_ID=<your-access-key>
AWS_SECRET_ACCESS_KEY=<your-secret-key>
AWS_DEFAULT_REGION=<your-region>

llm = LLM(
    model="bedrock/{model-id}"
)
```