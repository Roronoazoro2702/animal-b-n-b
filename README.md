# Animal BnB

## Description
Animal BnB is a Python-based application that connects pet owners looking to rent a cage (**guests**) with those offering cage space (**hosts**). It uses MongoDB for data storage and includes a CLI interface for user interaction.

## Features
- **Guest Mode**: Book a cage for your pet.
- **Host Mode**: Offer your extra cage space for rent.
- **MongoDB Integration**: Data persistence using MongoDB and MongoEngine.


```

## Dependencies
The project requires the following Python libraries:
- `pymongo`
- `mongoengine`
- `tqdm`
- `colorama`
- `python-dateutil`

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Roronoazoro2702/animal-b-n-b.git
   cd animal-b-n-b

   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up MongoDB**:
   - Ensure MongoDB is installed and running locally.

4. **Run the Application**:
   ```bash
   python program.py
   ```

## Usage
- **For Guests**: Select the option to book a cage.
- **For Hosts**: Select the option to offer your cage space.

Follow the prompts in the command-line interface to proceed.
