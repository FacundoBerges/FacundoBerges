<header align="center">
    <img alt="heading" src="https://capsule-render.vercel.app/api?type=waving&color=0:ff888c,100:fe0009&fontColor=fefefe&reversal=true&height=256&animation=fadeIn&text=Facundo%20Berges&fontSize=90&desc=Hola!%20soy&descAlign=10&descAlignY=15&descSize=30"/>
</header>

# Desarrollador fullstack, con conocimientos en Java para backend y Angular para frontend. ☕

## Sobre mí

```ts
// education-item.interface.ts
export interface EducationItem {
	title: string;
	technologies: string[];
	education_source?: string | string[];
	completion_year?: number;
}
```

```ts
// profile.interface.ts
import { EducationItem } from './education-item.interface';

export interface Profile {
	full_name: string;
	location: string;
	education: EducationItem[];
	ongoing_learning?: string[];
	current_year_objectives: string[];
	interests: string[];
	hobbies: string[];
}
```

### Información:

```ts
// main.ts
import { Profile } from './profile.interface';

const user: Profile = {
	full_name: 'Facundo Hector Berges',
	location: 'Ciudad Autónoma de Buenos Aires, Argentina',
	education: [
		{
			title: 'Tecnicatura Universitaria en Programación',
			technologies: [
				'C', 'Codeblocks', 'Eclipse', 'Arduino',
				'C#', 'Visual studio', 'Microsoft SQL Server', 'Windows forms',
				'Bash', 'JavaScript', 'HTML', 'CSS', 'Visual Studio Code', 
				'MySQL', 'MySQL workbench', 'NodeJS', 'Postman',
				'MongoDB', 'MongoSH', 'TypeScript', 'Angular', 'NestJS',
			], // Sorted by learning date.
			education_source:
				'Universidad Tecnológica Nacional - facultad regional Avellaneda (UTN-FRA)',
			completion_year: 2025,
		},
		{
			title: 'Desarrollador/programador autodidacta',
			technologies: [ 
				'HTML', 'CSS', 'SASS', 'Bootstrap', 'TailwindCSS',
				'MySQL', 'Java', 'Spring', 'Spring data', 'Spring security', 
				'JavaScript', 'TypeScript', 'Angular'
			],
			education_source: ['Documentaciones oficiales', 'YouTube', 'Platzi', 'DevTalles'],
			completion_year: undefined,
		},
		{
			title: 'Desarrollador Java',
			technologies: ['Java', 'MySQL', 'JDBC'],
			education_source: 'UTN BA',
			completion_year: 2023,
		},
		{
			title: 'Desarrollo backend - Especialización Spring',
			technologies: ['Java', 'MySQL', 'Spring Boot', 'Spring Data', 'JUnit', 'Mockito'],
			education_source: 'Codo a codo',
			completion_year: 2023,
		},
		{
			title: 'Desarrollo web Full Stack Java',
			technologies: ['Java', 'MySQL', 'JDBC', 'JSP', 'HTML', 'CSS', 'JavaScript'],
			education_source: 'Codo a codo',
			completion_year: 2023,
		},
		{
			title: 'Programación web Full Stack',
			technologies: ['Java', 'MySQL', 'JDBC', 'JPA', 'Spring', 'HTML', 'CSS', 'JavaScript'],
			education_source: 'Egg cooperation',
			completion_year: 2023,
		},
		{
			title: 'JavaScript',
			technologies: ['JavaScript', 'HTML', 'CSS', 'Bootstrap'],
			education_source: 'Coderhouse',
			completion_year: 2022,
		},
		{
			title: 'Desarrollo web',
			technologies: ['HTML', 'CSS', 'SASS', 'Bootstrap'],
			education_source: 'Coderhouse',
			completion_year: 2021,
		},
	],
	ongoing_learning: ['MongoDB', 'NestJS', 'Golang', 'Docker', 'UX/UI'],
	current_year_objectives: [
		'Aprender sobre aplicaciones autocontenidas',
		'Desarrollar 5 aplicaciones',
	],
	interests: [
		'Desarrollo Web',
		'Código de calidad',
		'Arquitectura de software',
		'DevOps',
		'UI/UX',
	],
	hobbies: ['Escuchar música', 'Tomar mate y/o café', 'Jugar videojuegos', 'Ver series y animes'],
};

console.table(user);
```

## Tecnologías aprendidas:

### Algunas de las tecnologías que utilizo:

#### Lenguajes:

![Lenguajes](https://go-skill-icons.vercel.app/api/icons?theme=light&perline=10&i=html,css,java,js,ts)

#### Bases de datos SQL/NoSQL:

![Bases de datos](https://go-skill-icons.vercel.app/api/icons?theme=light&perline=10&i=mysql,mongodb,postgresql,sqlserver)

#### Gestores de paquetes/dependencias:

![Bases de datos](https://go-skill-icons.vercel.app/api/icons?theme=light&perline=10&i=maven,npm)

#### Frameworks:

![Frameworks](https://go-skill-icons.vercel.app/api/icons?theme=light&perline=10&i=bootstrap,tailwind,hibernate,spring,springdatajpa,nodejs,angular)

#### IDE's y editores de código:

![IDE's y editores de código](https://go-skill-icons.vercel.app/api/icons?theme=light&perline=10&i=vscode,idea)

#### Librerías:

![Librerías](https://go-skill-icons.vercel.app/api/icons?theme=light&perline=10&i=sass,junit,reactivex,primeng,mongoose)

#### Otras herramientas utilizadas durante el camino:

![Otras herramientas aprendidas durante el camino](https://go-skill-icons.vercel.app/api/icons?theme=light&perline=10&i=git,github,regex,api,json,postman,jwt,nestjs,supabase,expressjs,lucidchart,uml,netlify,prettier,apache,tomcat,chromedevtools,jquery,excel,word,outlook,teams,slack,terminal,wsl,windows,bash,mint,ubuntu,linux,visualstudio,cs,arduino,eclipse,c)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="github-contribution-grid-snake.svg" />
</picture>

<footer align="center">
    <div>
        <img alt="footer" src="https://capsule-render.vercel.app/api?section=footer&height=200&type=blur&reversal=true&color=gradient&fontColor=fefefe&animation=fadeIn&text=Contactame!&fontAlign=50&fontAlignY=45&fontSize=55&textBg=false"/>
    </div>
    <div style="position: relative; display: flex; justify-content: center">
        <div align="center" style="position: absolute; top:-74px; border-radius:10px;padding:5px 0 0">
            <a target="_blank" title="LinkedIn" href="https://www.linkedin.com/in/facundo-berges" style="text-decoration: none; padding: 5px;">
                <img alt="LinkedIn Logo" src="./images/linkedin-logo.svg" height=60 />
            </a>
            <a target="_blank" title="GMail" href="mailto:facundo.h.berges@gmail.com" style="text-decoration: none; padding: 5px;">
                <img alt="GMail Logo" src="./images/gmail-logo.svg" height=60 />
            </a>
            <a target="_blank" title="GitHub" href="https://github.com/FacundoBerges/" style="text-decoration: none; padding: 5px;">
                <img alt="GitHub Logo" src="./images/github-logo.svg" height=60 />
            </a>
        </div>
    </div>
</footer>
