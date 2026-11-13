# Security Operations Incident-Management (COMP3010)

### Local LLM Implementation
Partnered AI working with a local LLM is required to attain top marks. I will be using Ollama as recommended by JJ.

This repository will hold a folder with files that are required/streamline setting up a local LLM on lab machines.

This is required as lab computers only hold temporary storage.

## AI Setup
The LLM Model that I will be running locally on lab machines is <b>Gemma4:31b</b>.
<br></br>
The "Modelfile" includes the configuration required to create a customised gemma4:31b model. It defines... 
- Parameters for generation, 
- Preferences for writing style, 
- Rules on how to handle evidence, 
- Assumption formatting,
- Instructions tailored tailored to intrusion analysis

Ollama must be installed manually via the installer each time as lab machines do not allow running scripts. 
The gemma model must also be pulled each time (with 'ollama pull gemma4:31b')
<br></br>
## Evidence Portfolio
Within this repository, there is an evidence portfolio, which includes evidence necessary to demonstrate authentic investigation
- Portions of bulk AI logs (methodology & prompts/queries)
- Screenshots and working from coursework validation questions investigation (including packet captures and stream analysis)
- Logs, timelines and other relevant artefacts
- Use of AI logs, methodology and sample prompt/queries