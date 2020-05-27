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
> - Time commitment: String[64] //"int unit freq"
> - Dates needed: String[16][64]
> - Date posted: String[64]
       
# Queries
> ## organization
> - POST (Name, Email, Location, URL, Description)
> - PUT (?)
> - DELETE(Email)
> - GET (Email)

> ## opporotunity
> - POST (Title, Type, Description_brief, Location, Time, Dates, Organization, description_full)
> - PUT (?)
> - DELETE (Title, organization)
> - GET (Title, organization)


