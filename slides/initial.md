---
layout: default
routeAlias: initial
---

<div class="text-center">
    <h1 class="text-3xl font-bold text-indigo-800 mb-2">多医疗智能体协作会诊</h1>
    <p class="text-gray-600">专家智能体做出初步判断</p>
</div>

<div class="grid grid-cols-3 gap-12 h-full items-center -mt-8">

<div v-click=1 class="v-click">
  <div class="relative bg-red-50 rounded-2xl p-3 shadow-lg hover:shadow-xl transition-all duration-300">
    <div class="absolute -top-6 left-1/2 -translate-x-1/2">
      <carbon:medication class="text-4xl text-red-600 bg-white rounded-full p-2 shadow-md" />
    </div>
    <h3 class="text-xl font-bold text-red-800 mb-4 mt-2"><Link to="doctor1">专家智能体 1</Link></h3>
    <div class="text-sm leading-relaxed">
      <div class="mb-2 -mt-2">
        <div class="flex justify-between mb-2">
          <span><carbon:warning class="flex-shrink-0 text-red-500 mr-2" /> 风险等级</span>
          <span>55%</span>
        </div>
        <div class="h-2 bg-gray-200 rounded-full overflow-hidden">
          <div class="w-55/100 h-full bg-red-600 animate-progress"></div>
        </div>
      </div>
      <div>
        <div class="flex justify-between mb-2">
          <span><carbon:warning class="flex-shrink-0 text-red-500 mr-2" />重点关注特征</span>
        </div>
        <div class="bg-white rounded-lg">
          <li>二氧化碳结合力</li>
          <li>白蛋白</li>
          <li>营养摄入</li>
        </div>
      </div>
    </div>
  </div>
</div>

<div v-click=1 class="v-click">
  <div class="relative bg-green-50 rounded-2xl p-3 shadow-lg hover:shadow-xl transition-all duration-300">
    <div class="absolute -top-6 left-1/2 -translate-x-1/2">
      <carbon:medication class="text-4xl text-emerald-600 bg-white rounded-full p-2 shadow-md" />
    </div>
    <h3 class="text-xl font-bold text-green-800 mb-4 mt-2"><Link to="doctor2">专家智能体 2</Link></h3>
    <div class="text-sm leading-relaxed">
      <div class="mb-2 -mt-2">
        <div class="flex justify-between mb-2">
          <span><carbon:warning class="flex-shrink-0 text-green-500 mr-2" /> 风险等级</span>
          <span>17%</span>
        </div>
        <div class="h-2 bg-gray-200 rounded-full overflow-hidden">
          <div class="w-1/6 h-full bg-green-500 animate-progress"></div>
        </div>
      </div>
      <div>
        <div class="flex justify-between mb-2">
          <span><carbon:warning class="flex-shrink-0 text-green-500 mr-2" />重点关注特征</span>
        </div>
        <div class="bg-white rounded-lg">
          <li>舒张压</li>
          <li>血氯</li>
          <li>血肌酐</li> 
        </div>
      </div>  
    </div>
  </div>
</div>

<div v-click=1 class="v-click">
  <div class="relative bg-purple-50 rounded-2xl p-3 shadow-lg hover:shadow-xl transition-all duration-300">
    <div class="absolute -top-6 left-1/2 -translate-x-1/2">
      <carbon:medication class="text-4xl text-purple-600 bg-white rounded-full p-2 shadow-md" />
    </div>
    <h3 class="text-xl font-bold text-purple-800 mb-4 mt-2"><Link to="doctor3">专家智能体 3</Link></h3>
    <div class="text-sm leading-relaxed">
      <div class="mb-2 -mt-2">
        <div class="flex justify-between mb-2">
          <span><carbon:warning class="flex-shrink-0 text-red-800 mr-2" /> 风险等级</span>
          <span>69%</span>
        </div>
        <div class="h-2 bg-gray-200 rounded-full overflow-hidden">
          <div class="w-7/10 h-full bg-red-800 animate-progress"></div>
        </div>
      </div>  
      <div>
        <div class="flex justify-between mb-2">
          <span><carbon:warning class="flex-shrink-0 text-red-800 mr-2" />重点关注特征</span>
        </div>
        <div class="bg-white rounded-lg">
          <li>血钾</li>
          <li>白蛋白</li>
          <li>收缩压/舒张压</li>
        </div>
      </div>  
    </div>
  </div>
</div>

</div>

<style>
/* 自定义气泡悬停动画 */
.hover\\:shadow-xl:hover {
  transform: translateY(-5px);
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

/* 对话三角箭头 */
.absolute > .w-0 {
  filter: drop-shadow(0 2px 4px rgba(0,0,0,0.1));
}
</style>