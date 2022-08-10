# NotionDatabase_CMS
This repository basically uses the Notin API and Integrates it into a Next.js + Tailwind app. 

### Installation
1. Fork the repository
2. npm install
3. Go to http://developers.notion.com/ and create a new integration.
3. Add ENV variables in .env.local file in root directory of the repository.
4. npm run dev

### Notion Integration
1. You'll need to go to http://developers.notion.com/ and create a new integration.
2. Go to the Notion database you want to connect and click on Share located on top right hand corner and select the integration there.
3. You are done with the Notion Integration, Copy the Secret API Key and enter it in .env.local .

### Environment Variables
Add Enviornment Variables in the .env.local file in the following manner

NOTION_API_KEY = 
NOTION_DATABASE_ID =

Database ID is basically the number at the end of the notion link of the page. Remeber that you have to provide the Database ID therefore you'll need to expand the database and copy and enter the ID here.

### Currently being used in :
- Internet Is Awesome (http://internetisawesome.xyz)
