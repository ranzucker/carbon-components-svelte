<script lang="ts">
  import { ComboBox } from "../types";
  import type { ComboBoxItem } from "../types/ComboBox/ComboBox";

  const items: ComboBoxItem[] = [
    { id: "0", text: "Slack" },
    { id: "1", text: "Email" },
    { id: "2", text: "Fax" },
  ];
</script>

<ComboBox
  direction="top"
  titleText="Contact"
  placeholder="Select contact method"
  items="{items}"
/>

<ComboBox
  titleText="Contact"
  placeholder="Select contact method"
  selectedIndex="{1}"
  items="{items}"
/>

<ComboBox
  light
  titleText="Contact"
  placeholder="Select contact method"
  items="{items}"
/>

<ComboBox
  titleText="Contact"
  placeholder="Select contact method"
  size="xl"
  items="{items}"
/>

<ComboBox
  titleText="Contact"
  placeholder="Select contact method"
  size="sm"
  items="{items}"
/>

<ComboBox
  disabled
  titleText="Contact"
  placeholder="Select contact method"
  items="{items}"
/>
