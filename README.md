VALHEIM SERVER RECOVERY
in the event something happens to this *very* old laptop hosting the server 
or (bob forbid) the whole house and people containing that laptop y'all can 
continue on! Yoshi and/or Jordan have hosted servers similarly in the past.
i'd solicit their help. but AI should also know what to do with a backed up
"worlds_local" folder. it should contain everything you need. cheers and
hinga dinga, everybody. -jeep

World name / -world argument: hinga dinga

This repository contains the complete worlds_local backup.
Use a complete snapshot; do not mix files from different backups.

Restore:
1. Install Valheim Dedicated Server on a replacement computer.
2. Keep the server stopped.
3. Copy the selected world snapshot into its worlds_local directory.
4. Set -world to the exact restored world basename.
5. If using a custom save location, set -savedir to the parent
   directory containing worlds_local, NOT to worlds_local itself.
6. Configure a new server password and the desired networking.
7. Start the server and verify familiar buildings and progression.

Other:
- Valheim version will be whatever's the most current, stable one released on steam
- No mods, just vanilla
- Character save data are client-side
