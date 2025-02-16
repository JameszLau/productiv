<script setup>
import { Button } from '@/components/ui/button'
import { HoverCard, HoverCardContent, HoverCardTrigger } from '@/components/ui/hover-card'
</script>

<template>
    <HoverCard>
        <HoverCardTrigger as-child>
        <Button variant="outline" class="text-slate-500 text-xs font-sans">
            <slot name="button-text">?</slot>
        </Button>
        </HoverCardTrigger>
        <HoverCardContent class="w-60">
        <div class="flex justify-between space-x-4">
            <div class="space-y-1">
            <h4 class="text-md font-semibold">
                <slot name="title">Enable us to help you focus</slot> <!-- Title passed from parent -->
            </h4>
            <p class="text-sm">
                <slot name="content">If you leave our page during a Pomodoro cycle, we will remind you to focus.</slot> <!-- Content passed from parent -->
            </p>
            </div>
        </div>
        </HoverCardContent>
    </HoverCard>

    <!-- for viewing component -->
    <!-- </div> -->
</template>

<style scoped>
    Button {
        box-shadow: none;
        margin: 0px 0px 0px 8px;
        padding: 0;
        height: 20px;
        width: 20px;
        border: solid;
        border-radius: 50%;
    }

    .hover-info-icon:Button {
    background-color: rgb(211, 211, 211);
    }
</style>