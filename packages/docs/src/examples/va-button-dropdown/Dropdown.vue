<template>
<div>
  <va-button-dropdown
    class="mr-2 mb-2"
    label="Will close dropdown on click"
    :close-on-click-inside="true"
  >
    Content
  </va-button-dropdown>

  <va-button-dropdown
    class="mr-2 mb-2"
    label="Will not close dropdown on click"
    :close-on-click-inside="false"
  >
    Content
  </va-button-dropdown>
</div>
</template>
