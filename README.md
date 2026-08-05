class ObaidQureshi:
    def __init__(self):
        self.name = "Obaid Qureshi"
        self.role = "Full Stack Developer"
        self.location = "Karachi, Pakistan"

        self.currently_learning = [
            "ASP.NET Core MVC",
            "SQL Server",
            "JavaScript"
        ]

        self.current_project = "Ghost - Number Guessing Game"
        self.goal = "Become a Professional Full Stack Developer"

    def say_hi(self):
        print(f"Hi, I'm {self.name} 👋")
        print("Passionate about building modern web applications.")
        print("Learning every day, building every day 🚀")

me = ObaidQureshi()
me.say_hi()
