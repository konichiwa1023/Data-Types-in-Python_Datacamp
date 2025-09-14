# Use a list comprehension to iterate over each penguin in penguins saved as female_species_list
# If the the sex of the penguin is 'FEMALE', return the species value
female_species_list = [penguin["species"] for penguin in penguins if penguin["sex"] == 'FEMALE']

# Create a set using the female_species_list as female_penguin_species
female_penguin_species = set(female_species_list)

# Find the difference between female_penguin_species and male_penguin_species. Store the result as differences
differences = female_penguin_species.difference(male_penguin_species)

# Print the differences
print(differences)
