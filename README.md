# ai201-project3-takemeter

**Community Choice**
r/leagueoflegends (subreddit)
-  Full of plenty of discourse, very active and large.  Some are very informative and encourage thoughtful, meaningful discussions, while also containing posts that may have little/no substantial reasoning but still invoke some thoughtful discussion. There are also a lot of posts that have no substance at all and are full of strong-willed people with even stronger opinions that serve essentially as just "noise".

**Label Taxonomy**
Labels:
SUBSTANTIVE ANALYSIS 
-(reasoning, evidence, explanation)
- Main purpose is to provide facts, explanations, guides, analysis, news, answers	"Is the author primarily trying to inform?"
- Contains reasoning, evidence, explanation, examples

OPINION / REACTION 
-(evaluations without substantial reasoning)
-Primarily emotional response, agreement/disagreement, short opinion
- Main purpose is evaluation, judgment, praise, criticism, preference, reaction	"Is the author primarily expressing what they think?"


LOW-INFORMATION / NOISE 
-(memes, insults, spam, very short content)
-Low-information content, memes, insults, spam, one-liners
-	Main purpose is soliciting interaction, debate, questions, speculation, conversation	"Is the author primarily trying to get others to engage?"

**Fine-tuning pipelines**
Base model use - distilbert-base-uncased (HuggingFace)
LLM use - Groq (llama-3.3-70b-versatile)
Fine-tuning	- Google Colab

**Training design**
I used batch size 16 because my GPU ran out of memory with batch size 32.
