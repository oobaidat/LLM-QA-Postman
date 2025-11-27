# LLM-QA-Postman

This project is a small automated QA system for LLM responses using **Postman**, **Google Gemini**, and **Webhook** for result export.

## Contents

- `LLM Automated QA.postman_collection.json`  
  Postman collection with:
  - Three test prompts (paris + cat + shopify)
  - API calls to Gemini-flash-2.0 to get answers
  - API calls to Gemini-flash-2.0 to evaluate the answers (returns JSON: `{verdict, reason}`)
  - Error-handling and result export request

- `LLM-QA-Env.postman_environment.json`  
  Template environment. **You must add your own Gemini API key and Webhook URL then share them for the monitor to run.**

- `demo-video-link.txt`  
  Link to a short video showing the creation and running of the scheduled monitor: https://drive.google.com/file/d/1arvqhie26_6isMGXIiEg26djbYkm5fl5/view?usp=sharing

## Notes

Postman workspace link: https://obaidat001-152848.postman.co/workspace/Osama-Obaidat's-Workspace~1dc8591a-5b7a-42b3-8510-b1f94dd0e58b/collection/50377666-a711a064-3188-4126-af27-d1a46bb86665?action=share&source=collection_link&creator=50377666
The monitor was deleted after the demo run.
