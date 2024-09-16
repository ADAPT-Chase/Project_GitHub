Installation
============

This section will guide you through the process of setting up Project_GitHub on your local machine.

Prerequisites
-------------

Before you begin, ensure you have the following installed on your system:

- Python 3.7 or higher
- Git

Steps
-----

1. Clone the repository:

   .. code-block:: bash

      git clone https://github.com/ADAPT-Chase/Project_GitHub.git
      cd Project_GitHub

2. (Optional) Create and activate a virtual environment:

   .. code-block:: bash

      python3 -m venv venv
      source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install the required dependencies:

   .. code-block:: bash

      pip install -r requirements.txt

4. Verify the installation:

   .. code-block:: bash

      python -m unittest discover tests

   If all tests pass, you have successfully set up Project_GitHub.

Next Steps
----------

Now that you have installed Project_GitHub, you can proceed to the :doc:`usage` section to learn how to use the project and its features.