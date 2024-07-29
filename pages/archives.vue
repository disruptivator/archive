<template>
<div class="max-w-lg mx-auto flex-grow"> 
    <div class="flex flex-wrap">
  <div class="border-e border-gray-200">
    <nav class="flex flex-col space-y-2" aria-label="Tabs" role="tablist" aria-orientation="horizontal">
      <button type="button" class="hs-tab-active:border-blue-500 hs-tab-active:text-blue-600 py-1 pe-4 inline-flex items-center gap-x-2 border-e-2 border-transparent text-sm whitespace-nowrap text-gray-500 hover:text-blue-600 focus:outline-none focus:text-blue-600 disabled:opacity-50 disabled:pointer-events-none active" id="vertical-tab-with-border-item-1" aria-selected="true" data-hs-tab="#vertical-tab-with-border-1" aria-controls="vertical-tab-with-border-1" role="tab">
        Tab 1
      </button>
      <button type="button" class="hs-tab-active:border-blue-500 hs-tab-active:text-blue-600 py-1 pe-4 inline-flex items-center gap-x-2 border-e-2 border-transparent text-sm whitespace-nowrap text-gray-500 hover:text-blue-600 focus:outline-none focus:text-blue-600 disabled:opacity-50 disabled:pointer-events-none" id="vertical-tab-with-border-item-2" aria-selected="false" data-hs-tab="#vertical-tab-with-border-2" aria-controls="vertical-tab-with-border-2" role="tab">
        Tab 2
      </button>
      <button type="button" class="hs-tab-active:border-blue-500 hs-tab-active:text-blue-600 py-1 pe-4 inline-flex items-center gap-x-2 border-e-2 border-transparent text-sm whitespace-nowrap text-gray-500 hover:text-blue-600 focus:outline-none focus:text-blue-600 disabled:opacity-50 disabled:pointer-events-none" id="vertical-tab-with-border-item-3" aria-selected="false" data-hs-tab="#vertical-tab-with-border-3" aria-controls="vertical-tab-with-border-3" role="tab">
        Tab 3
      </button>
    </nav>
  </div>

  <div class="ms-3">
    <div id="vertical-tab-with-border-1" role="tabpanel" aria-labelledby="vertical-tab-with-border-item-1">
      <p class="text-gray-500">
        This is the <em class="font-semibold text-gray-800">first</em> item's tab body.
      </p>
    </div>
    <div id="vertical-tab-with-border-2" class="hidden" role="tabpanel" aria-labelledby="vertical-tab-with-border-item-2">
      <p class="text-gray-500">
        This is the <em class="font-semibold text-gray-800">second</em> item's tab body.
      </p>
    </div>
    <div id="vertical-tab-with-border-3" class="hidden" role="tabpanel" aria-labelledby="vertical-tab-with-border-item-3">
      <p class="text-gray-500">
        This is the <em class="font-semibold text-gray-800">third</em> item's tab body.
      </p>
    </div>
  </div>
</div>
    </div>
    
</template>
