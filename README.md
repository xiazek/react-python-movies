# React Python Movies

Deployed at https://react-python-movies-cspk.onrender.com/

## How to run

### Backend (FastAPI)
1. Go to `api` directory
2. Install dependencies: `pip install -r requirements.txt`
3. Start the application: `uvicorn main:app --reload`

### Frontend (React)
1. Go to `ui` directory
2. Install dependencies: `npm install`
3. Start the application: `npm start`

## Deployment

This application is deployed on Render.

### How to deploy changes
To deploy changes to Render, push your code to the main branch of the repository connected to Render:
```bash
git push origin main
```
Render will automatically detect the changes and rebuild the application based on the `Dockerfile`.


# Komentarz do prowadzącego

Większa część oczekiwanych na piątkę elementów została dodana ;) :

 - [x] Dodaj obsługę błędów - w przypadku błędnej odpowiedzi serwera poinformuj o tym użytkownika, np. za pomocą biblioteki react-toastify
 - [x] Zapytaj użytkownika, czy na pewno chce usunąć film po kliknięciu w przycisk usuwania. Być może też react-toastify okaże się użyteczne?
 - [ ] Dodaj animacje ładowania, gdy frontend czeka na odpowiedź serwera. Przykłady: https://loading.io/css/.
 - [ ] Pobaw się animacjami w React by ożywić interfejs Twojej aplikacji.
 - [x] Dodaj listę aktorów (podlgąd, jacy aktorzy występują w systemie>
 - [x] Pozwól na edycję filmów (nazwy i opisu).
 - [x] Dodaj wyszukiwarkę filmów. Być może opartą o wektorową bazę danych? :)


PS. Sam jestem współautorem serwisu kino.krakow.pl który jest trochę bardziej rozwiniętą wersją tego projektu. Prowadzę go z kolegą od 25 lat.. ;) 
