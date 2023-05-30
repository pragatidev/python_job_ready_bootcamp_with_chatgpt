# Frequently Asked Questions (FAQ)

This document lists some of the most frequently asked questions about the Python installation process.

## Python Installation

**Q1: I'm getting an error during Python installation, what should I do?**

- Ensure you have sufficient permissions on your computer to install new software. If you're on a work or school
  computer, you may need to ask your system administrator for help.
- Make sure your operating system meets the Python installation requirements. Python 3.x requires a computer with an
  operating system that is currently receiving updates and security patches from its manufacturer.
- If the installation continues to fail, try downloading the Python installer again, it may be corrupted.

**Q2: I've installed Python, but when I check the version, it shows a different one. Why is this happening?**

This issue is likely due to the PATH environment variable pointing to a different Python version. Follow the PATH setup
instructions in the `installation_guide.md` document to correctly set up your PATH.

## Setting up the PATH Environment Variable

**Q3: How do I know if Python has been added to my PATH environment variable?**

You can check whether Python has been added to your PATH by opening a new terminal or command prompt and
typing `python --version`. If the system responds with the Python version, then Python has been added to your PATH.

**Q4: I've followed the PATH setup instructions, but my terminal still doesn't recognize Python. What should I do?**

Make sure to restart your terminal/command prompt after changing your PATH variable, as the changes will only take
effect in new terminal windows. If you still encounter issues, verify that the directory you've added to your PATH
actually contains the Python executable.

## General

**Q5: Can I have more than one Python version installed on my computer?**

Yes, you can have multiple Python versions installed on your computer. However, the `python` command will use the
version that appears first on your PATH. If you want to use different versions for different projects, consider using a
version manager like pyenv.

**Q6: I'm stuck, and my question isn't answered here. Where can I get additional help?**

Feel free to ask questions in the Udemy course forum. The course community and the instructor are there to help you. If
you encounter a specific error, a quick web search can also yield helpful results. Python has a strong community, and
it's likely that someone else has encountered and solved the same problem.

Please note that this FAQ will be updated as more questions come in. Thanks for being a part of this learning journey!
