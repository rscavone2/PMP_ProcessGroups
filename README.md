# PMP_ProcessGroups
Neo4js Cypher for graphing and mapping relations between processes and process groups as outlined in PMBOK 6th Edition

# Define Lists
BodiesOfKnowl = ["integration",
                 "scope",
                 "stakeholder",
                 "costs",
                 "communication",
                 "resources",
                 "risks",
                 "quality",
                 "procurement"]

process_groups = ["initiating",
                  "planning",
                  "executing",
                  "monitor_control",
                  "closing"]
      
    
#     processes
#

#     itto_types
#       inputs
#       tools
#       techniques
#       outputs


# Relationship ?constraints?

# BodiesOfKnowl encompass the processes within process_groups

# process_groups can occur within multiple BodiesOfKnowl

# processes are unique and unique to the process_groups in which they are a "processOf"

# itto_types are not unique; they can be multi directional as related to the processes in which they are an itto_of based on their type.
