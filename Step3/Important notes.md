I had to recreate the index and indexer because initially I didn't select the right fields for the Keyphrase enrichment during the index creation. This caused issues during the custom-entities enrichment as I was wrongly overwriting the instructor field.

Also there are two index fields that are always null because I was making some tests creating different fields with different settings (sortable, filterable...). Recreating all index, indexer and skillsets takes too much time so I'll leave it as it is for now.