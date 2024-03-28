# Grant Application Review Optimization

Implementing the Cross-industry Process of Data Mining (CRISP-DM) to streamline university grant application reviews.

## Project Overview

The project addresses the inefficiencies in the university grant application review process by applying CRISP-DM. The goal is to enhance the quality of grant applications, identifying potential issues early in the process to ease the burden on both the grants department and applicants.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Features](#features)
4. [Contributing](#contributing)
5. [License](#license)
6. [Acknowledgements](#acknowledgements)

## Installation

Provide detailed instructions on setting up the project, including the installation of Alteryx and necessary dependencies.

## Usage

Guide users on how to leverage Alteryx predictive tools for implementing CRISP-DM in the grant application review process. Include examples and best practices.

## Features

- Applies CRISP-DM methodology
- Utilizes Alteryx predictive tools for modeling
- Selects the best modeling technique for validation
- Flags potential issues in grant applications early in the process

## Streamlined Approvals

In this phase of the project, various models were created and applied to a test set to evaluate accuracy. To streamline the grant application review process, we propose the implementation of a "quick no" policy, including:

1. **High-level Application:**
   - Applicants submit a high-level application with compulsory fields required by our models.

2. **Establishing Approval Threshold:**
   - Set an approval threshold at 20% probability of success in the top two or three models.

3. **Filtering Process:**
   - Connect a Filter tool to remove applications with less than a 20% chance of approval in the selected models.

### Benefits

- **Time Savings:**
  - Reduces the time spent on reviewing applications with low chances of success.

- **Resource Optimization:**
  - Efficiently allocates resources for both the applicants and the university.

## Implementation Steps

1. **Filter Tool Configuration:**
   - Connect a Filter tool to the dataset.
   - Select the Custom filter radio option.

2. **Formula Expression:**
   - Filter applications with less than a 20% chance of approval in the top two or three models.

## Conclusion

By implementing this approach, the university can significantly reduce workload and save valuable time and resources. This streamlined process ensures that only applications with a reasonable chance of success undergo detailed review.

## Contributing

If you wish to contribute, please follow the guidelines outlined.

## License

This project is licensed under the [Your License] - see [LICENSE.md](LICENSE.md) for details.

## Acknowledgements

- Recognition to the Alteryx community for tools and support
- Appreciation to Dr. Ebuka Ibeke.
