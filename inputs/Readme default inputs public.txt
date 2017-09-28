The file "BSM Default Inputs" contains many of the model input default values.
If you would like to restore input values, you can import it into Stella. This file is in the models\Data folder. In the BSM-public.STMX in Stella, use the following steps to import:

Model --> Import Data

You should see 18 Import Links that have BSM_Default_Inputs.xlsx as the Source. Activate each link by clicking the check boxes in the "Active" column.

Confirm these settings:
-Sheet Orientation is "Horizontal"
-Link Type is "On Demand"
-Import Behavior is "Set parameters"

Click "Import All"

If these pre-established links are no longer in your version of the model, they can be re-established using the following steps:  

Click on the "+" sign.

Browse for the file and worksheet. You will need a separate link for each worksheet.

Choose "Set parameters (will overwrite...)" as Import Behavior.

Choose "On Demand" as Link Type. [This option is not available if you have “Control variables” selected instead of “Set parameters (will overwrite...)"]

Choose "Horizontal" as Sheet Orientation.

Click "Import All"