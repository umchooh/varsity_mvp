# Varsity Project MVP
This example demonstrates a full MVP functionality for Create, Read, Update, and Delete. The relationships can also be modified through the web interface.

![Listing Players](https://github.com/christinebittle/varsity_mvp/blob/master/varsity_w_auth/assets/listplayers.png)

![Showing Player](https://github.com/christinebittle/varsity_mvp/blob/master/varsity_w_auth/assets/showplayer.png)

![Updating a player](https://github.com/christinebittle/varsity_mvp/blob/master/varsity_w_auth/assets/updateplayer.png)


![Listing Sponsors](https://github.com/christinebittle/varsity_mvp/blob/master/varsity_w_auth/assets/listsponsors.png)


![Update Sponsor](https://github.com/christinebittle/varsity_mvp/blob/master/varsity_w_auth/assets/updatesponsor.png)
![Show Sponsor](https://github.com/christinebittle/varsity_mvp/blob/master/varsity_w_auth/assets/showsponsor.png)


![Show Team](https://github.com/christinebittle/varsity_mvp/blob/master/varsity_w_auth/assets/showteam.png)


## To Run This Project
- Clone Codebase
- **Right Click Project > View Project in File Explorer > Create Folder "App_Data"**
- Tools > Nuget Package Manager > Package Manager Console
- enable-migrations
- add-migration {migration_name}
- update-database
- update portnumber in PlayerController.cs, TeamController.cs, SponsorController.cs

## Common Issues
### Unable to access part of path ... roslyn/csc.exe
- Right click solution > Clean
- Right click solution > Build
- Right click solution > Rebuild

### Update Database failed. Could not create .mdf file
- Create "App_Data" Folder in project

### The name or namespace 'Script'/'JavaScriptSerializer' could not be found
- Right click "References"
- Add System.Web.Extensions

### Every Action says something went wrong
- Update the port number to the current port your local project is using
- update portnumber defined in PlayerController.cs, TeamController.cs, SponsorController.cs

### Adding a player leads to an error
- Add a team first, each player must play for a team

References
- [Previous Project PetGrooming](https://github.com/christinebittle/PetGroomingMVC)
- [Previous Project BlogProject 7th iteration](https://github.com/christinebittle/BlogProject_7)
- [Utilized Lightbox plugin by Lokesh Dhakar](https://lokeshdhakar.com/projects/lightbox2/)
