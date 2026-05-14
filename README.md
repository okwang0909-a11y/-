<!-- TOP GRAPH CARD -->
<div class="absolute right-[160px] top-[60px] w-[440px] h-[300px] rounded-[34px] bg-white border border-[#e8edf2] panel-shadow overflow-hidden">

  <div class="flex items-center justify-between px-10 pt-8">

    <div class="text-[28px] font-semibold text-[#1e1e1e]">
      Weekly Stats
    </div>

    <div class="text-[40px] leading-none">
      ···
    </div>

  </div>

  <!-- graph area -->
  <div class="relative px-8 mt-6">

    <!-- horizontal lines -->
    <div class="absolute left-8 right-8 top-3 space-y-10 opacity-70">
      <div class="border-t border-[#dfe5ea]"></div>
      <div class="border-t border-[#dfe5ea]"></div>
      <div class="border-t border-[#dfe5ea]"></div>
      <div class="border-t border-[#dfe5ea]"></div>
    </div>

    <svg width="370" height="140" viewBox="0 0 370 140" class="relative z-10">

      <path
        d="M0 85
           C30 95, 45 40, 80 55
           C115 70, 140 5, 180 20
           C220 35, 245 120, 290 85
           C320 60, 335 -10, 370 15"
        fill="none"
        stroke="#7CC8B5"
        stroke-width="6"
        stroke-linecap="round"
      />

      <path
        d="M0 120
           C20 125, 40 70, 70 95
           C100 120, 120 60, 150 85
           C180 110, 210 55, 240 105
           C260 135, 290 40, 320 55
           C340 60, 350 55, 370 55"
        fill="none"
        stroke="#7671D9"
        stroke-width="6"
        stroke-linecap="round"
      />

    </svg>

  </div>

  <!-- labels -->
  <div class="flex justify-between px-14 mt-2 text-[18px] text-[#808991]">
    <span>07</span>
    <span>03</span>
    <span>36</span>
    <span>13</span>
    <span>16</span>
    <span>67</span>
  </div>

  <!-- legend -->
  <div class="flex gap-10 px-14 mt-6 text-[18px]">

    <div class="flex items-center gap-3 text-[#616a74]">
      <div class="w-4 h-4 rounded-full bg-[#7CC8B5]"></div>
      Events
    </div>

    <div class="flex items-center gap-3 text-[#616a74]">
      <div class="w-4 h-4 rounded-full bg-[#7671D9]"></div>
      Inqueries
    </div>

  </div>

</div>

<!-- FLOATING SHOP ICON -->
<div class="absolute right-[110px] top-[230px] w-[110px] h-[110px] rounded-[28px] bg-white panel-shadow flex items-center justify-center">

  <svg width="52" height="52" viewBox="0 0 24 24" fill="none">
    <path d="M4 5H6L8.2 14.5C8.4 15.3 9.1 16 10 16H18C18.8 16 19.5 15.4 19.7 14.6L21 8H7"
      stroke="#111"
      stroke-width="1.8"
      stroke-linecap="round"
      stroke-linejoin="round"/>
    <circle cx="10" cy="20" r="1.8" fill="#111"/>
    <circle cx="18" cy="20" r="1.8" fill="#111"/>
  </svg>

</div>

<!-- BOTTOM ANALYTICS PANEL -->
<div class="absolute left-[300px] bottom-[60px] w-[740px] h-[390px] rounded-[36px] bg-white border border-[#e7ecf0] panel-shadow overflow-hidden">

  <div class="flex items-center justify-between px-12 pt-10">

    <div class="text-[28px] font-semibold text-[#1e1e1e]">
      Activity
    </div>

    <div class="text-[40px] leading-none">
      ···
    </div>

  </div>

  <!-- DONUT -->
  <div class="absolute left-[55px] top-[120px]">

    <div class="text-[20px] font-medium text-[#444] mb-5">
      Budget Scord
    </div>

    <div class="flex items-center gap-10">

      <div
        class="relative w-[180px] h-[180px] rounded-full"
        style="
          background:
          conic-gradient(
          #8CB8EA 0 22%,
          #7CC4C8 22% 38%,
          #72D2AE 38% 58%,
          #8A7CE5 58% 73%,
          #6BC9B0 73% 88%,
          #7DB6D0 88% 100%);
        "
      >

        <div class="absolute inset-[34px] bg-white rounded-full"></div>

      </div>

      <!-- legend -->
      <div class="space-y-4 text-[18px] text-[#505b66]">

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#8CB8EA]"></div>
          Fead
        </div>

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#7CC4C8]"></div>
          Transport
        </div>

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#8A7CE5]"></div>
          Ranchland
        </div>

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#72D2AE]"></div>
          Rent
        </div>

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#7DB6D0]"></div>
          AutoFront
        </div>

      </div>

    </div>

  </div>

  <!-- bars -->
  <div class="absolute right-[55px] top-[130px] w-[320px]">

    <div class="relative h-[180px] flex items-end justify-between">

      <!-- grid -->
      <div class="absolute inset-0 flex justify-between">
        <div class="w-[1px] bg-[#e7ebef] h-full"></div>
        <div class="w-[1px] bg-[#e7ebef] h-full"></div>
        <div class="w-[1px] bg-[#e7ebef] h-full"></div>
        <div class="w-[1px] bg-[#e7ebef] h-full"></div>
        <div class="w-[1px] bg-[#e7ebef] h-full"></div>
        <div class="w-[1px] bg-[#e7ebef] h-full"></div>
        <div class="w-[1px] bg-[#e7ebef] h-full"></div>
      </div>

      <div class="w-5 h-[82px] bg-[#746BDA] rounded-full relative z-10"></div>
      <div class="w-5 h-[60px] bg-[#83B6E7] rounded-full relative z-10"></div>
      <div class="w-5 h-[112px] bg-[#71D1AE] rounded-full relative z-10"></div>
      <div class="w-5 h-[72px] bg-[#6DC6AF] rounded-full relative z-10"></div>
      <div class="w-5 h-[108px] bg-[#7E74DE] rounded-full relative z-10"></div>
      <div class="w-5 h-[66px] bg-[#71D1AE] rounded-full relative z-10"></div>
      <div class="w-5 h-[112px] bg-[#83B6E7] rounded-full relative z-10"></div>

    </div>

    <!-- labels -->
    <div class="flex justify-between mt-6 text-[18px] text-[#7d8690]">
      <span>01</span>
      <span>02</span>
      <span>03</span>
      <span>04</span>
      <span>25</span>
      <span>06</span>
      <span>27*</span>
    </div>

  </div>

</div>

<!-- LIME ICON -->
<div class="absolute left-[245px] bottom-[250px] w-[84px] h-[84px] rounded-[24px] bg-[#D8F14B] shadow-[0_12px_24px_rgba(180,220,50,.35)] flex items-center justify-center">

  <svg width="42" height="42" viewBox="0 0 24 24" fill="none">
    <path d="M7 4H17L19 7L12 14L5 7L7 4Z"
      stroke="#111"
      stroke-width="1.8"
      stroke-linejoin="round"/>
    <circle cx="12" cy="18" r="4"
      stroke="#111"
      stroke-width="1.8"/>
  </svg>

</div>

<!-- BLACK CREDIT CARD -->
<div class="absolute left-[70px] top-[140px] w-[560px] h-[370px] rounded-[34px] credit-card panel-shadow overflow-hidden">

  <!-- curves -->
  <div class="curve w-[500px] h-[500px] right-[-270px] top-[-120px]"></div>
  <div class="curve w-[450px] h-[450px] right-[-245px] top-[-95px]"></div>
  <div class="curve w-[400px] h-[400px] right-[-220px] top-[-68px]"></div>
  <div class="curve w-[350px] h-[350px] right-[-195px] top-[-42px]"></div>

  <div class="relative z-10 h-full px-12 py-14 flex flex-col justify-between">

    <!-- top -->
    <div class="flex justify-between">

      <div>

        <div class="text-white/80 text-[22px] font-medium mb-8">
          Main Balance
        </div>

        <div class="text-white text-[64px] font-bold tracking-tight">
          $984,556.34
        </div>

      </div>

      <div class="text-white/80 text-[26px] tracking-[4px] mt-3">
        **** **** **** 1234
      </div>

    </div>

    <!-- bottom -->
    <div class="flex items-end justify-between">

      <div class="flex gap-16">

        <div>

          <div class="text-white/45 text-[20px] font-medium mb-3">
            VALID THRU
          </div>

          <div class="text-white text-[48px] font-semibold leading-none">
            08/21
          </div>

        </div>

        <div>

          <div class="text-white/45 text-[20px] font-medium mb-3">
            CARD HOLDER
          </div>

          <div class="text-white text-[48px] font-semibold leading-none">
            Roberto Karloz
          </div>

        </div>

      </div>

      <!-- mastercard -->
      <div class="relative w-[92px] h-[60px] mr-4 mb-2">
        <div class="absolute left-0 top-0 w-[60px] h-[60px] rounded-full bg-[#b2b54b] opacity-70"></div>
        <div class="absolute right-0 top-0 w-[60px] h-[60px] rounded-full bg-[#d0d35d] opacity-70"></div>
      </div>

    </div>

  </div>

</div>
