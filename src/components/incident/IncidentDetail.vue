<template>

</template>

<script>
    data(); {
        return {
            incidents: [{id: 1, 
            title: 'Connectivity issues', 
            update_set: [{
                'title': 'Connectivity issues: slow response time API', 
                'description': 'We are experiencing connectivity issues on our API. We are investigating this issue and will keep you up to date on this.', 
                'date': '2018-9-12 12:30:00', 
                'status': 'identified'}, 
                {'title': 'We are still investigating this issue.', 
                'description': 'We are still working hard on investigating this issue. We appreciate your support and patience.', 
                'date': '2018-8-23 12:23:23', 
                'status': 'investigating'}]}],
            incident: []
        }
    }
</script>

<style scoped>

</style>