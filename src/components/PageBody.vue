<template>
    <div>
       <h1>BODY</h1>
       <side-panel></side-panel>
       <meet-the-developer></meet-the-developer>
       <meet-the-team></meet-the-team>
    </div>
</template>

<script>
import SidePanel from "./SidePanel";
import MeetTheDeveloper from "./MeetTheDeveloper";
import MeetTheTeam from "./MeetTheTeam";
    export default {
        name: "page-body",
        components: {
            SidePanel,
            MeetTheDeveloper,
            MeetTheTeam,
        }
    }
</script>

<style scoped>
h1{
    color: chartreuse;
}
</style>