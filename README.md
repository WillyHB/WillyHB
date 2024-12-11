```rust
struct ReadMe {
    name: String,
    interests: Vec<&'static str>,
    languages: Vec<&'static str>,
    favourite_languages: String,
}

impl ReadMe {
    fn new() -> Self {
        ReadMe {
            name: "William Hansen-Baird".to_string(),
            interests: vec!["Music", "Gamedev", "Pixel Art", "Video Games"],
            languages: vec!["Rust", "C#", "Javascript", "Html", "CSS", "C++", "C", "Bash"],
            favourite_languages: "C#/Rust".to_string(),
        }
    }

    fn display_greeting() {
        println!("Welcome to my profile :)");
    }
}

```
