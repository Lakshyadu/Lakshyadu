struct Developer {
    name: &'static str,
    role: &'static str,
    current_focus: &'static str,
    tools: Vec<&'static str>,
    interests: Vec<&'static str>,
}

fn main() {
    let lakshya = Developer {
        name: "Lakshya Dubey",
        role: "Aspiring Data Analyst",
        current_focus: "Data Analytics + Generative AI",

        tools: vec!["SQL", "Python", "Power BI", "Tableau", "Advanced Excel"],

        interests: vec![
            "Data Cleaning & EDA",
            "Dashboard Reporting",
            "Machine Learning",
            "LLMs",
            "RAG",
            "AI-Assisted Analytics",
        ],
    };

    println!("Turning raw data into decisions. Learning every day. 🚀");
}
