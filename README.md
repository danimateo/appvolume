## Usage

Place this somewhere in your path with execute permissions.

1. List applications with current volume and muted status

   ``appvol l``

   This produces:

   ``` 
   1) Chromium - 100%
   2) SuperTuxKart - 50% MUTED
   ```

2. Toggle muting an application. If only one is playing sound it mutes it without displaying the list.

   ``appvol m``
   This produces:
   ```
   1) Chromium
   2) SuperTuxKart
   Select an input sink: 1
   Chromium was muted
   ```

3. Set volume of an application (percentages). If only one is playing sound it sets the volume without displaying the list.

    Example: ``appvol 50``
    This produces:
    ```
    1) Chromium
    1) SuperTuxKart
    Select an input sink: 1
    Volume for Chromium was set to 50%
    ```