<template>
  <section class="py-20 bg-white">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">이력 소개</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <!-- Card 1: 학력 -->
        <div class="bg-blue-50 p-6 rounded-xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2">🎓 학력</h3>
          <p>고려대학교 바이오의공학과 졸업<br />(Bioengineering, KU)</p>
        </div>

        <!-- Card 2: 프로젝트 -->
        <div class="bg-blue-50 p-6 rounded-xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2">🔬 연구 프로젝트</h3>
          <p>DNA 데이터 저장 기술 연구<br />BioChip 논문 발표</p>
        </div>

        <!-- Card 3: 수상 -->
        <div class="bg-blue-50 p-6 rounded-xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2">🏆 수상 경력</h3>
          <p>LG전자 iPBL 대회 최우수상<br />식기세척기 건조기술 제안</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// 특별한 로직 없음
</script>

<style scoped>
/* 필요 시 카드 간 마진 또는 아이콘 스타일 추가 가능 */
</style>
