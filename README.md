# Firefighter Ontology Project

This repository contains the Firefighter ontology, designed to model emergency response roles in fire incidents with a focus on Vrije Universiteit Amsterdam. The ontology aims to improve emergency response coordination and planning by providing a structured representation of events, personnel, locations, and schedules related to firefighting efforts.

## Overview

The ontology includes classes for events, persons, opening times, locations, and more, allowing for granular, role-based queries essential for emergency response. The instance data is created with accuracy concerning location information and simulated data for incidents to maintain privacy.

## Repository Structure

- `instance level`: Contains Turtle files with instance data for the ontology.
  - `accident_data.ttl`: Simulated accident events data.
  - `accidents_linked_to_shifts_responsibilities.ttl`: Links accidents to shifts and responsibilities.
  - `floor_room_dataset.ttl`: Spatial data of the university buildings.
  - `opening_time_data.ttl`: Operating times of the buildings.
  - `shift_times.ttl`: Shift times of emergency personnel.
- `schema level`: Contains the ontology schema file.
  - `firefighting.owl`: OWL file defining the structure and semantics of the ontology.
- `README.md`: Provides documentation and guidance for using this repository.

## Using the Ontology

To use the Firefighter ontology, please ensure that you have an RDF store or an ontology editor like Protégé.

1. Clone the repository:
2. Load the `firefighting.owl` file into your ontology editor.
3. To add instance data, import the `.ttl` files from the `instance level` directory into your RDF store.

## Contribution Guidelines

If you would like to contribute to the ontology:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or fix.
3. Commit your changes with clear commit messages.
4. Push your changes to your fork.
5. Create a pull request to the original repository.

Please provide detailed information on your pull request, including the reasons for your changes and any references to relevant issues or discussions.

## Contact

If you have any questions or feedback, please open an issue in the GitHub repository or contact the maintainers at [email address].

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments

Special thanks to the contributors and domain experts who provided valuable insights during the creation of this ontology.
