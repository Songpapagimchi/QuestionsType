<template>
    <div>
        <div class="flex w-full h-2/4 justify-center items-top mt-5">
            <div class="w-full max-w-xs">
                <table>
                    <tr>
                        <td rowspan="2" >
                            <img :src="iconImg.Target">
                        </td>
                        <td class="font-bold text-s text-left text-gray-600">
                            나의 차량 스타일
                        </td>
                    </tr>
                    <tr>
                        <td class="font-bold text-xs text-left text-gray-400">
                            나의 차량 취향 스타일을 확인해요
                        </td>
                    </tr>
                </table>
                <div class="bg-white p-3 rounded-lg shadow-xl w-full mt-3">
                    <span class="flex sinline-grid grid-cols-2 gap-2">
                        <span>abc</span>
                        <span>def</span>
                    </span>
                </div>
            </div>
        </div>
        <div class="flex w-full h-3/4 justify-center items-top mt-5">
            <div class="w-full max-w-xs">
                <table>
                    <tr>
                        <td rowspan="2" >
                            <img :src="iconImg.MyChar">
                        </td>
                        <td class="font-bold text-s text-left text-gray-600">
                            나의 차량 스타일
                        </td>
                    </tr>
                    <tr>
                        <td class="font-bold text-xs text-left text-gray-400">
                            나의 차량 취향 스타일을 확인해요
                        </td>
                    </tr>
                </table>
                <div class="bg-white p-3 rounded-lg shadow-xl w-full mt-3">

                </div>
            </div>
        </div>
    </div> 
</template>

<script setup>
    import { reactive } from 'vue'
    
    const iconImg = reactive({
        Target: 'assets/icon_Target.png',
        MyChar: 'assets/icon_MyChar.png'
    })
</script>