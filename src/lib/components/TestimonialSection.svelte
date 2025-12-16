<script>
    import { ArrowLeft, ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-[#F9F7F2] py-24 overflow-hidden">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <!-- Navigation Buttons -->
        <div class="flex justify-end gap-2 mb-8">
            <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center bg-white hover:bg-gray-50 transition-colors text-gray-400 hover:text-gray-900">
                <ArrowLeft size={16} />
            </button>
            <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center bg-white hover:bg-gray-50 transition-colors text-gray-400 hover:text-gray-900">
                <ArrowRight size={16} />
            </button>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <!-- Quote Content -->
            <div class="pr-8">
                <div class="mb-8">
                    <span class="text-sm font-bold tracking-widest uppercase">MANUFACTURING LEADER</span>
                </div>
                <blockquote class="text-2xl md:text-3xl font-light text-gray-900 leading-relaxed mb-12">
                    "Emerix transformed our supply chain operations from reactive to proactive. What used to take our team days of manual ERP work now happens autonomously. We've reduced stockouts by 40% and freed our team to focus on strategic supplier relationships instead of data entry."
                </blockquote>
                <div>
                    <div class="font-medium text-gray-900">Sarah Chen</div>
                    <div class="text-[10px] uppercase tracking-widest text-gray-500 mt-1">Chief Operating Officer, $600M Manufacturing Company</div>
                </div>
            </div>

            <!-- Image -->
            <div class="relative h-[600px] w-full overflow-hidden">
                <img 
                    src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?q=80&w=2076&auto=format&fit=crop" 
                    alt="Supply chain professional" 
                    class="absolute inset-0 h-full w-full object-cover grayscale contrast-125"
                />
            </div>
        </div>
    </div>
</section>
