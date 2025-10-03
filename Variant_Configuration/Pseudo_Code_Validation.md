# Pseudo-Code for VC Validation

if Material == "PVC" and Pressure > 200:
    raise ConfigurationError("PVC cannot exceed 200 PSI")

if Size == "Large" and Material == "PVC":
    raise ConfigurationError("Large PVC valves not allowed")
