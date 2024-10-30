# algorithms-and-data-structures_ex2
C++ program that implements a user data management system. This system should allow users to be added, 
all users to be displayed, and users to be sorted by age using the mergesort algorithm.

Requirements:
User class:

Fields: string name, int age.
Methods:
A constructor that initializes both fields.
A function to display user data.
UserManager class:

Field: vector<User> users.
Methods:
void addUser(string name, int age) - adds a new user.
void displayUsers() - displays a list of users.
void sortUsersByAge() - sorts users by age using mergesort.
Helper functions:

void merge(vector<User> &users, int left, int mid, int right) - merges two sorted parts of a vector.
void mergesort(vector<User> &users, int left, int right) - sorts the vector of users using mergesort.
