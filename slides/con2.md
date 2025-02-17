---
layout: default
---

<div class="text-center -mt-5">
    <h1 class="text-3xl font-bold text-indigo-800 mb-2">多医疗智能体协作会诊流程</h1>
    <p class="text-gray-600">专家智能体的多轮协作讨论</p>
</div>

<div class="grid grid-cols-3 gap-8 h-full max-w-4xl mx-auto">
  <div class="relative bg-red-50 rounded-2xl p-3 shadow-lg hover:shadow-xl transition-all duration-300">
    <div class="absolute -top-6 left-1/2 -translate-x-1/2">
        <carbon:ai class="text-4xl text-red-600 bg-white rounded-full p-2 shadow-md" />
    </div>
    <h3 class="text-xl font-bold text-red-800 mb-4 mt-2">专家智能体 2</h3>
    <div class="space-y-2 text-sm leading-relaxed">
        <div class="flex justify-between text-xs -mt-3">
            <span><carbon:warning class="flex-shrink-0 text-red-500 mr-2" /> 风险等级</span>
            <span>55%</span>
        </div>
        <div class="h-2 bg-gray-200 rounded-full overflow-hidden">
            <div class="w-55/100 h-full bg-red-600 animate-progress"></div>
        </div>
        <div class="bg-white rounded-lg">
            <li>二氧化碳结合力18.7 mmol/L，显著低于ESRD患者参考范围（>25 mmol/L），提示存在代谢性酸中毒，可能导致肌肉消耗及肾病进展加速</li>
            <li>白蛋白30.2 g/L，低于ESRD患者参考范围 （>32 g/L），提示低蛋白血症，可能增加感染风险及营养不良相关并发症</li>
            <li>高营养摄入（3495.67 g），可能掩盖实际存在的营养吸收不良或代谢需求增加</li>
        </div>
    </div>
  </div>

  <div class="relative top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-64">
    <div class="bg-indigo-50 rounded-lg p-3 border border-indigo-200">
      <h3 class="font-bold text-indigo-800 text-center text-sm mb-2">综合报告</h3>
      <div class="text-xs text-gray-600 leading-tight">
        <li>高风险状态</li>
        <li>代谢性酸中毒</li>
        <li>低蛋白血症</li>
        <li>营养代谢矛盾</li>
      </div>
    </div>
  </div>

  <div class="relative">
    <div class="relative bg-red-50 rounded-2xl p-3 shadow-lg hover:shadow-xl transition-all duration-300">
      <div class="absolute -top-6 left-1/2 -translate-x-1/2">
        <carbon:ai class="text-4xl text-red-600 bg-white rounded-full p-2 shadow-md" />
      </div>
      <h3 class="text-xl font-bold text-red-800 mb-4 mt-2">专家智能体 1</h3>
      <div class="space-y-2 text-sm leading-relaxed">
        <div class="bg-white rounded-lg">
          MetaAgent的观点揭示了我初始分析中未充分评估的高危因素：代谢性酸中毒、低白蛋白血症及低钾血症，这些是终末期肾病患者死亡风险升高的重要标志。
          <br>
          这些关键病理特征的综合作用支持MetaAgent关于高死亡风险的结论，需通过纠正代谢紊乱、营养支持及电解质管理进行多靶点干预。
        </div>
      </div>
    </div>
  </div>
</div>