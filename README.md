### Hi there 👋 If you need more info, just let me know...

class Profile {
    constructor(name,lastname,gitProfile,birthday,linkedin){
        this.name= name;
        this.lastname= lastname;
        this.gitProfile= gitProfile;
        this.birthday= birthday;
        this.linkedin= linkedin;
        this.certificates={
            'HTML/CSS': 'CODERHOUSE',
            'JAVASCRIPT': 'CODERHOUSE',
            'REACT JS': 'CODERHOUSE',
            'NODE JS' : 'CODERHOUSE'
        }
    }
    knowledgementAcquired(){
        return {
            'FRONTEND':['Html', 'Css / Sass', 'Javascript', 'React Js', 'Bootstrap'],
            'BACKEND':['Node Js' , 'Express'],
            'DATABASE':['MongoDb / Mongoose / Mongo Atlas', 'Firebase' , 'MySql'],
            'TOLLS':['Git' , 'Github', 'Gitlab', 'Storybooks', 'Visualcode', 'IntellIj Idea', 'Postman'],
            'AGILE METHODOLOGIES':'Kanban',
        }
    }
}

const Otar = new Profile('Otar','Kebadze','OtarKebadze','8 August 1990','https://www.linkedin.com/in/otarkebadze/')

--------------------------------------------------------------------------------------------------------------------------

<!--
**OtarKebadze/OtarKebadze** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
