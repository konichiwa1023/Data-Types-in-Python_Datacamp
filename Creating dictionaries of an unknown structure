# Create an empty dictionary: female_penguin_weights
female_penguin_weights = {}

# Iterate over the weight_log entries
for species, sex, body_mass in weight_log:
    # Check to see if species is already in the dictionary
    if species not in female_penguin_weights:
        # Create an empty list for any missing species
        female_penguin_weights[species] = []
    # Append the sex and body_mass as a tuple to the species keys list
    female_penguin_weights[species].append((sex, body_mass))
    
# Print the weights for 'Adlie'
print(female_penguin_weights['Adlie'])
