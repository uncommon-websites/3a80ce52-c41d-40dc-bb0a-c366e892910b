<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Autonomous Workflows<br />Within Your ERP
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Procurement Automation -->
            <div class="group">
                <div class="mb-6 bg-[#0B231E] rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-green-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">Auto-Generate Purchase Orders</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-green-700">
                                <Check size={12} /> <span class="text-gray-600">Running workflow...</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Analyzing inventory levels</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Checking supplier lead times</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Creating POs in NetSuite</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Procurement Automation</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    AI agents automatically generate purchase orders based on inventory levels, demand forecasts, and supplier performance. Eliminate manual PO creation and reduce stockouts.
                </p>
            </div>

            <!-- Card 2: Inventory Optimization -->
            <div class="group">
                <div class="mb-6 bg-[#0B231E] rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">SKU reorder point analysis</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-[oklch(0.696_0.17_162.48)] rounded flex items-center justify-center text-white text-[8px]">AI</div>
                            <span class="text-[10px] text-gray-400">Analyzed 847 SKUs</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>SKU</div>
                                <div class="col-span-2 text-right">Days to Stockout</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-red-400 rounded-sm"></div> SKU-4729</div>
                                <div class="col-span-2 h-1.5 bg-red-100 rounded w-1/4 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-yellow-400 rounded-sm"></div> SKU-8832</div>
                                <div class="col-span-2 h-1.5 bg-yellow-100 rounded w-1/2 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-green-400 rounded-sm"></div> SKU-2156</div>
                                <div class="col-span-2 h-1.5 bg-green-100 rounded w-3/4 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Inventory Optimization</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Monitor inventory levels in real-time and automatically adjust reorder points based on demand patterns, seasonality, and supplier lead times to optimize working capital.
                </p>
            </div>

            <!-- Card 3: Demand Planning -->
            <div class="group">
                <div class="mb-6 bg-[#0B231E] rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-[oklch(0.696_0.17_162.48)] rounded flex items-center justify-center text-white text-[8px]">D</div>
                            <span class="text-[10px] text-gray-500">Generating forecast report...</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            Q2 demand forecast complete. Updated production schedules and material requirements in NetSuite.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-blue-500 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Q2 Demand Forecast.xlsx</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-green-600 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Material Requirements.xlsx</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Demand Planning</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    AI-powered demand forecasting that analyzes historical data, market trends, and seasonality to generate accurate production schedules and material requirements.
                </p>
            </div>
        </div>
    </div>
</section>
