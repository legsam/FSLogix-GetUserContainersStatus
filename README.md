# FSLogix-GetUserContainersStatus

This script retrieve the current user FSLogix containers status. It collects information for both profile and Office Containers.

# Usage: 
Launch the script from the user session to retrieve all FSLogix containers informations:
  - Profile Container stores error values here: HKLM\Software\FSLogix\Profiles\Sessions\<UserSID>
  - FSLogix Office Container stores error values in two places: HKLM\Software\Policies\FSLogix\ODFC\Sessions\<UserSID> and HKCU\Software\FSLogix\ODFC\Sessions

# Sample return:

