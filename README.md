Exam Scheduling for University
This repository contains a Python-based system for automating the scheduling of exams for a university. The system utilizes an algorithm that employs binary encoding of chromosomes, fitness evaluation, and selection/crossover mechanisms to generate optimal exam schedules.

Features
Course representation: The system includes classes for courses, student registrations, and exams, allowing for efficient management of course data and exam scheduling.
Conflict resolution: The algorithm handles constraints such as student enrollment, exam duration, time slot availability, and invigilator assignments to avoid conflicts and ensure fair scheduling.
Fitness evaluation: A fitness function is used to evaluate the quality of each generated exam schedule, enabling the system to optimize the allocation of resources and time slots.
Randomization: The system incorporates randomization techniques to ensure diverse and unbiased exam schedules.
Documentation: The code is well-documented with clear explanations of classes, methods, and algorithms to facilitate understanding and further development.
Requirements
Python 3.x
Additional dependencies mentioned in the requirements.txt file.
Usage
Clone the repository:

shell
Copy code
git clone https://github.com/Legolas2215/ExamSchedulingForUniversity.git
Install the required dependencies:

shell
Copy code
pip install -r requirements.txt
Execute the main program:

shell
Copy code
python main.py
Follow the on-screen instructions to input course data, student registrations, and generate the exam schedule.

Contributing
Contributions are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request. Make sure to follow the guidelines mentioned in the repository's CONTRIBUTING.md file.

License
This project is licensed under the MIT License.

Acknowledgements
We would like to acknowledge the contributions and inspiration from various open-source projects and research papers that have helped shape and improve this system.
