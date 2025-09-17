# Create the empty list: labeled_entries
labeled_entries = []

# Iterate over the weight_log entries
for species, flipper_length, body_mass, sex in weight_log:
    # Append a new WeightEntry instance to labeled_entries
    labeled_entries.append(WeightEntry(species, flipper_length, body_mass, sex))
    
# Print a list of the first 5 mass_to_flipper_length_ratio values
print([entry.mass_to_flipper_length_ratio for entry in labeled_entries[:5]])
