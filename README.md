# Create Hero Interface

- hero.ts

## Create Componenets

- ng generate component heroes
- ng generate component hero-detail
- ng generate component messages
- ng generate component dashboard
- ng generate component hero-search

## Create Services

- ng generate service hero
- ng generate service message
- ng generate service InMemoryData
- npm install angular-in-memory-web-api --save


## Routes

- ng generate module app-routing --flat --module=app
- add routes 
- const routes: Routes = [
-  { path: '', redirectTo: '/dashboard', pathMatch: 'full' },
-   { path: 'dashboard', component: DashboardComponent },
-   { path: 'detail/:id', component: HeroDetailComponent },
-   { path: 'heroes', component: HeroesComponent },
- ];

## 