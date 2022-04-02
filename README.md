# Random-FiveM-guides-Custom-Replace-biler-og-mere
# Lav en mappe som jeg viser i videoen med en __resource i og en "stream" mappe, hvor du smider alle ytd og yft filer ind.


# En __resource fil plejer at se sådanne ud:




resource_manifest_version '77731fab-63ca-442c-a67b-abc70f28dfa5'
 
files {
    'vehicles.meta',    -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
    'carvariations.meta',      -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
    'carcols.meta',     -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
    'handling.meta',    -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
    'vehiclelayouts.meta',    -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
}

data_file 'HANDLING_FILE' 'handling.meta'       -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
data_file 'VEHICLE_METADATA_FILE' 'vehicles.meta'       -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
data_file 'CARCOLS_FILE' 'carcols.meta'     -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
data_file 'VEHICLE_VARIATION_FILE' 'carvariations.meta'     -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
data_file 'VEHICLE_LAYOUTS_FILE' 'vehiclelayouts.meta'      -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen


client_script {
    'vehicle_names.lua'    -- Hvis du ikke har sådanne en fil i din mappe, skal du sætte 2 streger "--" foran linjen
}
