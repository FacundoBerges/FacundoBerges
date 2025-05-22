<header>
    <img alt="heading" src="https://capsule-render.vercel.app/api?type=waving&color=0:ff888c,100:fe0009&fontColor=fefefe&reversal=true&height=256&animation=fadeIn&text=Facundo%20Berges&fontSize=90&desc=Hola!%20soy&descAlign=10&descAlignY=15&descSize=30"/>
</header>

# Sobre mí

```ts
// main.ts
import { User } from './user.interface';

const user: User = {
	full_name: 'Facundo Hector Berges',
	located_in: 'Ciudad Autónoma de Buenos Aires, Argentina',
	education: [
		{
			title: 'Tecnicatura Universitaria en Programación',
			technologies: [
				'C',
				'C#',
				'JavaScript',
				'HTML',
				'CSS',
				'MySQL',
				'NodeJS',
				'MongoDB',
				'TypeScript',
				'Angular',
				'NestJS',
			],
			place: 'Universidad Tecnológica Nacional - facultad regional Avellaneda (UTN-FRA)',
			end_year_or_expected: 2025,
		},
		{
			title: 'Desarrollador/programador autodidacta',
			technologies: [
				'JavaScript',
				'HTML',
				'CSS',
				'Java',
				'SASS',
				'MySQL',
				'Spring',
				'TypeScript',
				'Angular',
			],
			place: ['YouTube', 'Platzi', 'DevTalles'],
			end_year_or_expected: undefined,
		},
		{
			title: 'Desarrollador Java',
			technologies: ['Java', 'MySQL', 'JDBC'],
			place: 'UTN BA',
			end_year_or_expected: 2023,
		},
		{
			title: 'Desarrollo backend - Especialización Spring',
			place: 'Codo a codo',
			technologies: ['Java', 'MySQL', 'Spring Boot', 'Spring Data', 'JUnit', 'Mockito'],
			end_year_or_expected: 2023,
		},
		{
			title: 'Desarrollo web Full Stack Java',
			place: 'Codo a codo',
			technologies: ['Java', 'MySQL', 'JDBC', 'JSP', 'HTML', 'CSS', 'JavaScript'],
			end_year_or_expected: 2023,
		},
		{
			title: 'Programación web Full Stack',
			technologies: ['Java', 'MySQL', 'JDBC', 'JPA', 'Spring', 'HTML', 'CSS', 'JavaScript'],
			place: 'Egg cooperation',
			end_year_or_expected: 2023,
		},
		{
			title: 'JavaScript',
			technologies: ['JavaScript', 'HTML', 'CSS', 'Bootstrap'],
			place: 'Coderhouse',
			end_year_or_expected: 2022,
		},
		{
			title: 'Desarrollo web',
			technologies: ['HTML', 'CSS', 'SASS', 'Bootstrap'],
			place: 'Coderhouse',
			end_year_or_expected: 2021,
		},
	],
	fields_of_interests: [
		'Desarrollo Web',
		'Código de calidad',
		'Arquitectura de software',
		'DevOps',
		'UI/UX',
	],
	currently_learning: ['MongoDB', 'NestJS', 'Docker', 'UX/UI'],
	current_year_goals: [
		'Conseguir empleo como desarrollador',
		'Aprender sobre aplicaciones autocontenidas',
		'Desarrollar 5 aplicaciones',
	],
	hobbies: ['Escuchar música', 'Ver series', 'Jugar videojuegos', 'Ver animes'],
};

console.table(user);
```

---

```ts
// user.interface.ts
import { Study } from './study.interface'

export interface User = {
    full_name: string;
    located_in: string;
    education: Study[];
    fields_of_interests: string[];
    currently_learning?: string | string[];
    current_year_goals: string | string[];
    hobbies: string[];
}
```

---

```ts
// study.interface.ts
export interface Study = {
    title: string;
    technologies: string[];
    place?: string | string[];
    end_year_or_expected?: number;
}
```

---

<footer>
    <div>
        <img alt="footer" src="https://capsule-render.vercel.app/api?section=footer&height=200&type=blur&reversal=true&color=gradient&fontColor=fefefe&animation=fadeIn&text=Contactame!&fontAlign=50&fontAlignY=45&fontSize=55&textBg=false"/>
    </div>
    <div style="position: relative; display: flex; justify-content: center">
        <div style="position: absolute; top:-74px; border-radius:10px;padding:5px 0 0">
        <p align="center">
            <a target="_blank" title="LinkedIn" href="https://www.linkedin.com/in/facundo-berges" style="text-decoration: none; padding: 5px;">
                <img alt="LinkedIn Logo" src="./images/linkedin-logo.svg" height=60 />
            </a>
            <a target="_blank" title="Gmail" href="mailto:facundo.h.berges@gmail.com" style="text-decoration: none; padding: 5px;">
                <img alt="Gmail Logo" src="./images/gmail-logo.svg" height=60 />
            </a>
            <a target="_blank" title="GitHub" href="https://github.com/FacundoBerges/" style="text-decoration: none; padding: 5px;">
                <img alt="GitHub Logo" src="./images/github-logo.svg" height=60 />
            </a>
        </p>
        </div>
    </div>
</footer>
