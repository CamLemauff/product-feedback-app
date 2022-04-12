<template>
    <div class="suggestions">
        <div class="left_panel">
            <div class="logo">
                <div class="logo_title">Frontend Mentor</div>
                <div class="logo_subtitle">Feedback Board</div>
            </div>

            <div class="filters">
                <div class="filter_active">All</div>
                <div class="filter">UI</div>
                <div class="filter">UX</div>
                <div class="filter">Enhancement</div>
                <div class="filter">Bug</div>
                <div class="filter">Feature</div>
            </div>

            <div class="roadmap">
                <div>Roadmap</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Suggestions',
  props: {
  }
}
</script>

<style scoped lang="scss">
  @import '../styles/styles.scss';

  .suggestions {
      display: flex;
      flex-direction: row;
      width: 90%;

      .left_panel {
          .logo {
            //   background-image: linear-gradient(to bottom right, #7AD8FB, radial-gradient(#E84D70, #A337F6, #28A7ED), #FBB57A);
              background: radial-gradient(circle at 100% 100%, #FBB57A 0%, #E91E63 35%, #A337F6 66%, #28A7ED 93%);
              width: 255px;
              height: 137px;
              border-radius: 10px;
              display: flex;
              flex-direction: column;
              padding: 20px;
              justify-content: flex-end;

              .logo_title {
                  color: white;
                  font-family: 'Jost';
                  font-weight: 700;
                  font-size: 20px;
              }

              .logo_subtitle {
                  color: white;
                  font-family: 'Jost';
                  font-weight: 500;
                  font-size: 15px;
                  opacity: 75%;
              }
          }

          .filters {
              width: 255px;
              height: 166px;
              border-radius: 10px;
              background-color: white;
              display: flex;
              flex-direction: row;
              flex-wrap: wrap;
              padding: 20px;
              margin-top: 25px;

              .filter {
                  color: #4661E6;
                  background-color: #F2F4FF;
                  padding: 5px 15px;
                  margin: 0 5px;
                  font-family: 'Jost';
                  font-weight: 600;
                  height: 25px;
                  text-align: center;
                  display: flex;
                  align-items: center;
                  border-radius: 5px;
                  cursor: pointer;
              }

              .filter_active {
                  color: white;
                  background-color: #4661E6;
                  padding: 5px 15px;
                  margin: 0 5px;
                  font-family: 'Jost';
                  font-weight: 600;
                  height: 25px;
                  text-align: center;
                  display: flex;
                  align-items: center;
                  border-radius: 5px;
                  cursor: pointer;
              }
          }
      }
  }
</style>