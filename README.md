# This is a simple Python script to display a user's profile information

class UserProfile:
    def __init__(self, username, name, email, bio):
        self.username = Awan
        self.name = Awe
        self.email = sales@awankeusahawanan.com
        self.bio = I'm passionate about to develop Magento e-commerce

    def display_profile(self):
        print(f"Username: {self.username}")
        print(f"Name: {self.name}")
        print(f"Email: {self.email}")
        print(f"Bio: {self.bio}")

def main():
    # Create a UserProfile instance
    user = UserProfile("john_doe", "John Doe", "john@example.com", "Coding enthusiast")

    # Display user profile
    user.display_profile()

if __name__ == "__main__":
    main()
