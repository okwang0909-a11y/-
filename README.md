<!-- top chart card -->
<div class="absolute right-[170px] top-[80px] w-[440px] h-[310px] bg-white rounded-[34px] border border-[#e8edf2] card-shadow overflow-hidden">

  <div class="px-10 pt-8 flex items-center justify-between">

    <div class="text-[28px] font-semibold text-[#1e1e1e]">
      Weekly Stats
    </div>

    <div class="text-[40px] leading-none -mt-3">
      ···
    </div>

  </div>

  <!-- graph -->
  <div class="relative px-8 mt-6">

    <!-- grid -->
    <div class="absolute inset-0 top-[10px] px-8">
      <div class="space-y-10 opacity-70">
        <div class="border-t border-[#dfe5ea]"></div>
        <div class="border-t border-[#dfe5ea]"></div>
        <div class="border-t border-[#dfe5ea]"></div>
        <div class="border-t border-[#dfe5ea]"></div>
      </div>
    </div>

    <svg width="370" height="140" viewBox="0 0 370 140" class="relative z-10">

      <!-- green line -->
      <path
        d="M0 85
           C30 95, 40 40, 80 55
           C120 70, 130 5, 180 20
           C220 35, 240 120, 290 85
           C320 60, 330 -10, 370 15"
        fill="none"
        stroke="#7BC7B3"
        stroke-width="6"
        stroke-linecap="round"
      />

      <!-- purple line -->
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
      <div class="w-4 h-4 rounded-full bg-[#7BC7B3]"></div>
      Events
    </div>

    <div class="flex items-center gap-3 text-[#616a74]">
      <div class="w-4 h-4 rounded-full bg-[#7671D9]"></div>
      Inqueries
    </div>

  </div>

</div>

<!-- cart floating -->
<div class="absolute right-[110px] top-[250px] w-[108px] h-[108px] bg-white rounded-[28px] soft-shadow flex items-center justify-center">

  <svg width="52" height="52" viewBox="0 0 24 24" fill="none">
    <path d="M4 5H6L8.3 14.5C8.5 15.3 9.2 16 10 16H18C18.8 16 19.5 15.4 19.7 14.6L21 8H7"
      stroke="#111"
      stroke-width="1.8"
      stroke-linecap="round"
      stroke-linejoin="round"/>
    <circle cx="10" cy="20" r="1.7" fill="#111"/>
    <circle cx="18" cy="20" r="1.7" fill="#111"/>
  </svg>

</div>

<!-- bottom analytics card -->
<div class="absolute left-[310px] bottom-[70px] w-[730px] h-[390px] bg-white rounded-[36px] border border-[#e6ebef] card-shadow overflow-hidden">

  <div class="absolute left-0 top-0 bottom-0 w-[1px] bg-[#edf1f4]"></div>

  <div class="px-12 pt-10 flex items-center justify-between">

    <div class="text-[28px] font-semibold text-[#1e1e1e]">
      Activity
    </div>

    <div class="text-[40px] leading-none -mt-3">
      ···
    </div>

  </div>

  <!-- donut -->
  <div class="absolute left-[60px] top-[120px]">

    <div class="text-[20px] font-medium text-[#444] mb-5">
      Budget Scord
    </div>

    <div class="flex items-center gap-10">

      <div class="relative w-[180px] h-[180px] rounded-full"
           style="
           background:
           conic-gradient(
           #88B7E8 0 22%,
           #7CC4C9 22% 38%,
           #72D2AE 38% 58%,
           #8A7BE6 58% 73%,
           #6BC9B0 73% 88%,
           #79B6CF 88% 100%);
           ">

        <div class="absolute inset-[34px] bg-white rounded-full"></div>

      </div>

      <!-- legend -->
      <div class="space-y-4 text-[18px] text-[#505b66]">

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#88B7E8]"></div>
          Fead
        </div>

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#7CC4C9]"></div>
          Transport
        </div>

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#8A7BE6]"></div>
          Ranchland
        </div>

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#72D2AE]"></div>
          Rent
        </div>

        <div class="flex items-center gap-3">
          <div class="w-4 h-4 rounded-full bg-[#79B6CF]"></div>
          AutoFront
        </div>

      </div>

    </div>

  </div>

  <!-- activity bars -->
  <div class="absolute right-[55px] top-[135px] w-[320px]">

    <div class="relative h-[180px] flex items-end justify-between">

      <!-- grid -->
      <div class="absolute inset-0 flex justify-between">
        <div class="w-[1px] bg-[#e6eaee] h-full"></div>
        <div class="w-[1px] bg-[#e6eaee] h-full"></div>
        <div class="w-[1px] bg-[#e6eaee] h-full"></div>
        <div class="w-[1px] bg-[#e6eaee] h-full"></div>
        <div class="w-[1px] bg-[#e6eaee] h-full"></div>
        <div class="w-[1px] bg-[#e6eaee] h-full"></div>
        <div class="w-[1px] bg-[#e6eaee] h-full"></div>
      </div>

      <div class="w-5 h-[80px] bg-[#746BDA] rounded-full relative z-10"></div>
      <div class="w-5 h-[60px] bg-[#83B6E7] rounded-full relative z-10"></div>
      <div class="w-5 h-[110px] bg-[#71D1AE] rounded-full relative z-10"></div>
      <div class="w-5 h-[70px] bg-[#6DC6AF] rounded-full relative z-10"></div>
      <div class="w-5 h-[105px] bg-[#7E74DE] rounded-full relative z-10"></div>
      <div class="w-5 h-[65px] bg-[#71D1AE] rounded-full relative z-10"></div>
      <div class="w-5 h-[110px] bg-[#83B6E7] rounded-full relative z-10"></div>

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

<!-- lime icon -->
<div class="absolute left-[255px] bottom-[255px] w-[84px] h-[84px] rounded-[24px] bg-[#D9F24B] shadow-[0_12px_24px_rgba(180,220,50,.35)] flex items-center justify-center">

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

<!-- black credit card -->
<div class="absolute left-[80px] top-[150px] w-[560px] h-[370px] rounded-[34px] credit-card soft-shadow overflow-hidden">

  <!-- curve lines -->
  <div class="curve w-[480px] h-[480px] right-[-260px] top-[-100px]"></div>
  <div class="curve w-[430px] h-[430px] right-[-235px] top-[-78px]"></div>
  <div class="curve w-[380px] h-[380px] right-[-208px] top-[-52px]"></div>
  <div class="curve w-[330px] h-[330px] right-[-180px] top-[-28px]"></div>

  <div class="relative z-10 px-12 py-14 h-full flex flex-col justify-between">

    <div class="flex justify-between items-start">

      <div>

        <div class="text-white/80 text-[22px] font-medium mb-8">
          Main Balance
        </div>

        <div class="text-white text-[64px] font-bold tracking-tight">
          $984,556.34
        </div>

      </div>

      <div class="text-white/80 text-[26px] tracking-[4px] mt-4">
        **** **** **** 1234
      </div>

    </div>

    <div class="flex justify-between items-end">

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
      <div class="relative w-[90px] h-[60px] mr-4 mb-3">
        <div class="absolute left-0 top-0 w-[60px] h-[60px] rounded-full bg-[#b2b54b] opacity-70"></div>
        <div class="absolute right-0 top-0 w-[60px] h-[60px] rounded-full bg-[#d0d35d] opacity-70"></div>
      </div>

    </div>

  </div>

</div>
