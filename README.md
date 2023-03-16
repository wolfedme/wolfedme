### Hey there!
```rust
pub trait SoftwareEngineer{}
struct MaximilianWolf {
    role: Vec<String>,
    coding_skills: Vec<String>,
    locale: Vec<String>,
}

impl SoftwareEngineer for MaximilianWolf {
    fn get() -> Self {
        MaximilianWolf {
            role: vec!["Software Engineer", "IT Consultant", "Full Stack Dev"],
            coding_skills: vec!["Java", "Rust", "TypeScript", "Python"],
            locale: vec!["de_DE", "en_EN"],
        }
    }
}
```
