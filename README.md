# Frontend
#### Description
This web application's frontend is developed using Next.js. It consists of two main pages: a table page and a card page. The table page displays records in a tabular format, while the card page displays records in a card layout. Both pages include a universal search feature that filters records based on the movie title.

#### Commands to Run Frontend
0.change path:
> $ cd frontend
1.Install dependencies:
> $ npm install
2.Start the development server:
>  $ npm run dev

# Backend
#### Description
The backend of this web application is built using Python's FastAPI. It provides endpoints to handle CRUD operations for managing movie records. Additionally, it offers flexibility in data storage, allowing users to choose between different options such as MongoDB.

#### Commands to Run Backend
0.change path:
> $ cd backend
1.Install dependencies:
> $ pip install -r requirements.txt
2.Start the development server:
> $ uvicorn main:app --reload
