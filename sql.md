# Collections

> ## Organization
> - Name: String[32]
> - Description: String[256]
> - Website URL: String[128]
> - Location: String[64] //City, State
> - Unique ID: String[256]
> - Opporotunities: Opp[64]
> - Email: String[64]
    
> ## Opporotunity
> - Title: String[32]
> - Type: String[32]
> - Description_brief: String[128]
> - Description_full: String[512]
> - Location: String[128]
> - Organization: String[32]
> - Unique ID: String[256]
> - Time commitment: String[64] //"int unit freq"\>
> - People needed: Integer
> - People current: Integer
> - Dates needed: String[16][64]
> - Date posted: String[64]
       
# Queries (In JSON dict form)
> ## organization
> - POST (Name, Email, Location, URL, Description) -> UID | *only name and email are required*
> - PUT (UID, "items to be changed")
> - DELETE(UID)
> - GET (UID)

> ## opporotunity
> - POST (Title, Type, Description_brief, Location, Time, Dates, people_needed, Organization, description_full) -> UID
> - PUT (UID, "Items to be changed")
> - DELETE (UID)
> - GET (UID)


