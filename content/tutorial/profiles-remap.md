+++
title = "Setting Remaps"
weight = 303
+++


# Setting Remaps

When you click on a profile, you will see a table of remaps on the right side of the screen.

![screenshots](/images/tutorial/remaps_list.png)

Click on anything in this table, and this window will open:

![screenshots](/images/tutorial/remaps_modal.png)

In this menu, you can choose whether this button should be remapped, and if so, what it should
remap to.

## Policy

| Policy   | Explanation |
| :------: | :---------- |
| No Remap | This button will not be remapped. |
| Remap    | This button **will be remapped**. When this button is pressed, Reemap will send the buttons in the **output list** instead of the original button press. |

## Output List

A table of available outputs is shown on the right. If you click on an item, it will add an entry to
the **output list** shown on the left. You may add any number of outputs.

### Order of outputs

Reemap sends all the outputs as a batch, but the order of outputs might matter if one key acts
as a modifier for another.

For example, remapping to **Left Shift** and **B** results in a capital "B" being typed into
programs like Notepad. Remapping to **B** and **Left Shift**, however, results in a lowercase "b"
instead.

You can click on the arrow buttons to rearrange the outputs.

### Suppressing input

To suppress an input, set the policy to **Remap** but keep the output list empty.
