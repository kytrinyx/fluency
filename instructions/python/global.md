To work on an exercise, change to the directory of the exercise:

    cd hello-world

This contains the files for the exercise.

    .
    ├── README.md
    └── hello_world_test.py

To run a test file, pass it as an argument to the `python` command:

    python hello_world_test.py

If you want to stop the tests after the first failure, then you can use the pytest library.

Install pytest with pip:

    pip install pytest

Run the tests with the `py.test` command using the `-x` flag to exit after the first failure.

    py.test -x hello_world_test.py
