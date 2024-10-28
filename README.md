```python
# GitHub Profile Introduction
class GitHubProfile:
    def __init__(self, name, interests, skills, contact):
        self.name = name
        self.interests = interests
        self.skills = skills
        self.contact = contact
    def about_me(self):
        print(f"👋 Hi there! I'm {self.name}.")
        print("\n✨ Interests:")
        for interest in self.interests:
            print(f" - {interest}")
        print("\n🛠 Skills:")
        for skill in self.skills:
            print(f" - {skill}")
        print(f"\n📫 How to reach me: {self.contact}")

# Define profile details
profile = GitHubProfile(
    name="Anagha Manikathuparambil Baby",
    interests=["Artificial Intelligence", "Machine Learning", "Data Science",]
    skills=["Python", "SQL", "Git"],
    contact="am.anaghamb@gmail.com"
)

# Display profile details
profile.about_me()


<!---
AnaghaBaby123/AnaghaBaby123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
