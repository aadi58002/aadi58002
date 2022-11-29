<img src="./name.svg" alt="Aditya Yadav" style="display: flex;align-items: center;justify-content: center;">

<p>You can actual run the below code with the rustc main.rs name command<p>

```rust
#[derive(Debug)]
struct Person<'a> {
    prog_lang: (Vec<&'a str>, Vec<&'a str>, Vec<&'a str>, Vec<&'a str>),
    framework: (Vec<&'a str>, Vec<&'a str>, Vec<&'a str>, Vec<&'a str>),
    hobbies: (Vec<&'a str>, Vec<&'a str>, &'a str),
    interests: (Vec<&'a str>, Vec<&'a str>),
}

impl Person<'_> {
    fn new<'a>() -> Self {
        Person {
            prog_lang: (vec![], vec![], vec![], vec![]),
            framework: (vec![], vec![], vec![], vec![]),
            hobbies: (vec![], vec![], ""),
            interests: (vec![], vec![]),
        }
    }
}

fn languages<'a>(aditya_yadav: &mut Person) {
    let know_and_frequent_use = vec!["Rust", "Python", "JavaScript", "TypeScript", "Bash"];
    let know_and_rarely_use = vec!["C++", "Java"];
    let want_to_learn = vec!["Elisp", "Haskell", "Kotlin", "Go"];

    let data_representation_languages = vec!["Json", "Toml", "Yaml"];
    aditya_yadav.prog_lang = (
        know_and_frequent_use,
        know_and_rarely_use,
        want_to_learn,
        data_representation_languages,
    );
}

fn framework<'a>(aditya_yadav: &mut Person) {
    let know_frontend = vec!["Vue Js", "React Js", "Astro"];
    let know_full_stack = vec!["Next Js", "Nuxt Js"];
    let know_backend = vec!["Axum", "Node", "Express"];
    let know_database = vec!["redis-stack", "postgres", "mongodb"];

    aditya_yadav.framework = (know_frontend, know_backend, know_database, know_full_stack);
}

fn hobbies<'a>(aditya_yadav: &mut Person) {
    let fun_tech = vec![
        "Linux tools",
        "Automation",
        "Web Development frameworks",
        "Kubernetes",
    ];
    let fun_story = vec!["Manga", "Anime"];

    let fun_learning = "Unique Upcoming Frameworks and tools";

    aditya_yadav.hobbies = (fun_tech, fun_story, fun_learning);
}

fn interests<'a>(aditya_yadav: &mut Person) {
    let text_editor = vec!["Doom Emacs", "Neovim"];
    let linux = vec!["System utilities", "Unique upcoming tools"];

    aditya_yadav.interests = (text_editor, linux);
}

fn main() {
    let mut aditya_yadav: Person = Person::new();
    languages(&mut aditya_yadav);
    framework(&mut aditya_yadav);
    hobbies(&mut aditya_yadav);
    interests(&mut aditya_yadav);
    println!("{:#?}",aditya_yadav);
}
```

<p align="center">
    <img src="https://media.tenor.com/Si0MnDghJ-gAAAAC/shiro-no-game-no-life.gif" width="800" alt="Shiro No Game No Life GIF - Shiro No Game No Life Anime GIFs" style="max-width: 800px"/>
</p>

<p align="inline">
   <img src="https://github-readme-stats.vercel.app/api?username=aadi58002&show_icons=true&theme=dracula" alt="Aditya's GitHub stats">
</p>

<p align="inline">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aadi58002&layout=compact&theme=dracula" alt="Aditya's Languages used">
</p>

<p align="center">
    <img src="https://media.tenor.com/_KJnqjY37cgAAAAC/no-game-no-life-stare.gif" width="800" alt="No Game No Life Stare GIF - No Game No Life Stare Evil GIFs" style="max-width: 800px;"/>
</p>
