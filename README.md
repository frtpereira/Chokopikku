```ts
export class Info {

  name: string = 'Fábio Pereira'
  age: number = 26
  nationality: string = 'Portuguese'
  languages: Record<string, string>[] = [{ 'English': 'C1' }, { 'Portuguese': 'native' }]
  occupation: string = 'Go Dev || Software Engineer'
  university: string = 'Universidade Lusófona do Porto'
  freetime: string[] = ['Nature', 'Futsal', 'Classic Cars', 'Pool (billiard)']

}

export class Programming {

  languages: string[] = ['Golang', 'Java', 'Python', 'JS']
  stylesheets: string[] = ['CSS', 'Bootstrap']
  frameworks: string[] = ['Gin/Fiber', 'Spring', 'Django', 'React']
  databases: string[] = ['PostgreSQL', 'MongoDB', 'MySQL']
  cloud: string[] = ['AWS', 'Azure']
  infrastructure string[] = ['Terraform', 'Docker', 'Kubernetes']
  studying: string[] = ['Data Science']
  projects: string[] = [] // private

}

export class Social {

  github: string = 'frtpereira'
  linkedin: string = 'fabio-rafael-pereira'

}
```
