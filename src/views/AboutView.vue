<script>
    export default {
        data() {
            return {
                activeTab: 1,
                tech: [
                    {
                        id: 1,
                        name: 'HTML',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/1051/1051277.png',
                        status: '掌握'
                    },
                    {
                        id: 2,
                        name: 'CSS',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/732/732190.png',
                        status: '掌握'
                    },
                    {
                        id: 21,
                        name: 'SASS',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '掌握'
                    },
                    {
                        id: 91,
                        name: 'LESS',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '掌握'
                    },
                    {
                        id: 91,
                        name: 'uni-app',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '掌握'
                    },
                    {
                        id: 91,
                        name: 'Canvas',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '掌握'
                    },
                    {
                        id: 91,
                        name: 'Vite',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '掌握'
                    },
                    {
                        id: 91,
                        name: 'Hexo',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '掌握'
                    },
                    {
                        id: 4,
                        name: 'Javascript',
                        imageUrl: 'https://cdn.icon-icons.com/icons2/2415/PNG/512/javascript_original_logo_icon_146455.png',
                        status: '掌握'
                    },
                    {
                        id: 91,
                        name: 'TypeScript.js',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '掌握'
                    },
                    {
                        id: 7,
                        name: 'VueJS',
                        imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-vue-282497.png?f=webp',
                        status: '掌握'
                    },
                    {
                        id: 9,
                        name: 'NodeJS',
                        imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-node-js-1174925.png',
                        status: '掌握'
                    },
                    {
                        id: 91,
                        name: 'Express.js',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '掌握'
                    },
                    {
                        id: 12,
                        name: 'ReactJS',
                        imageUrl: 'https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-512.png',
                        status: '熟悉'
                    },
                    {
                        id: 3,
                        name: 'PHP',
                        imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-php-2038871-1720084.png',
                        status: '了解'
                    },
                    {
                        id: 31,
                        name: 'Java',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '了解'
                    },{
                        id: 31,
                        name: 'Sequlize',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '了解'
                    },{
                        id: 31,
                        name: 'linux',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '了解'
                    },
                    {
                        id: 31,
                        name: '其他前端生态圈',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '了解'
                    },
                ],
                tools: [
                    {
                        id: 1,
                        name: 'Git',
                        imageUrl: 'https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png',
                        status: 'Version Control'
                    },
                    {
                        id: 2,
                        name: 'GitHub',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/25/25231.png',
                        status: 'Git Hosting'
                    },
                    {
                        id: 3,
                        name: 'NPM',
                        imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-npm-3-1175132.png',
                        status: 'Package Manager'
                    },
                    {
                        id: 4,
                        name: 'MySQL',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/5968/5968313.png',
                        status: 'Database'
                    },
                    {
                        id: 5,
                        name: 'MongoDB',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: 'Database'
                    },
                    {
                        id: 5,
                        name: '码云GITEE',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: 'Git Hosting'
                    },
                    {
                        id: 5,
                        name: '其他...',
                        imageUrl: 'http://www.zhouyi.run/assets/maliao-8bcf1e95.webp',
                        status: '...'
                    },
                ]
            };
        }
    }
</script>
<template>
    <div
            class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5">
        <article data-page="about">

            <header>
                <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
                    About Us &nbsp;
                    <div class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate" data-aos="zoom-in-left"
                         data-aos-duration="600"></div>
                </div>
            </header>

            <section
                    class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center">
                <div class="flex justify-center">
                    <img class="w-9/12 rounded-full mb-3 fadein-up pict"
                         src="..\assets\团队.jpg" alt="Foto">
                </div>
                <div class="md:w-7/12">
                    <ul class="mb-3 md:mb-7 fadein-left fadeins-1">
                        <li class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">· 我们小组有组长：赵凯旋；</li>
                        <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">· 组员：邸赫炎、钟元、方卓然、牛彦如、王钰晟和朱宛悦。</li>
                        <li class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">· 我们是一个十分团结、欢快的小组，</li>
                        <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">· 小组成员之间互相帮助，在小组任务中互相激励，</li>
                        <li class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">· 缆车工作人员交流、蚊虫困扰、体力不支、天气闷热...我们克服了这些困难</li>
                        <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">· 在山上实习过程中的漫长的路途中互相鼓励，共同完成任务。</li>
                    </ul>
                    <ul class="mb-3 md:mb-7 fadein-left fadeins-2">
                        <li class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">· 在这次实习任务中我们小组</li>
                        <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">· 各尽其长、齐心协力、团结协作、积极努力的推进团队项目。</li>
                        <li class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">· </li>
                       <!-- <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">扫我微信/QQ加我吧</li>
                        <a target="_blank"
                           href="http://www.zhouyi.run:3001/api/v1/files/preview?p=6f0b0673e1a42ba952edfca76a557ca.png&amp;&amp;mimetype=image/png"
                        ><img width="100" height="100"
                              src="http://www.zhouyi.run:3001/api/v1/files/preview?p=6f0b0673e1a42ba952edfca76a557ca.png&amp;&amp;mimetype=image/png"
                        ></a><a target="_blank"
                                href="http://www.zhouyi.run:3001/api/v1/files/preview?p=d110c3b8573988728c2685d9a5889d2.png&amp;&amp;mimetype=image/png"
                    ><img width="100"
                          height="100"
                          src="http://www.zhouyi.run:3001/api/v1/files/preview?p=d110c3b8573988728c2685d9a5889d2.png&amp;&amp;mimetype=image/png"
                    ></a>-->
                    </ul>
                    <!--                    <p class="mb-3 fadein-left fadeins-2">-->
                    <!--                        &nbsp; &nbsp; &nbsp;-->
                    <!--                        我擅长使用各种前端技术，包括HTML、CSS、JavaScript等，并熟悉流行的前端框架和工具，如React、Vue.js和Webpack。我能够将设计师的视觉概念转化为现实，并确保网站在各种浏览器和设备上的兼容性。-->

                    <!--                        如果您正在寻找一位有经验、有创意的前端开发者，我很乐意为您提供服务。请通过下方提供的联系方式与我取得联系，让我们一起创造出令人印象深刻的网站吧！-->
                    <!--                    </p>-->
                </div>

            </section>

        </article>
    </div>
</template>

<style>
    .fadein-left {
        opacity: 0;
        font-size: 1.1rem;
        line-height: 2.2rem;
        animation: fadeInLeft 0.5s ease-out forwards;
    }

    @keyframes fadeInLeft {
        0% {
            opacity: 0;
            transform: translateX(100%);
        }

        100% {
            opacity: 1;
            transform: translateX(0);
        }
    }

    .fadeins-1 {
        animation-delay: 500ms;

    }

    .fadeins-2 {
        animation-delay: 800ms;
    }

    .img-tech,
    .tech {
        transition: transform 0.3s ease;
    }

    .item-tech:hover .img-tech {
        transform: scale(1.3);
    }

    .item-tech:hover .tech {
        transform: translateY(-12px);
    }

    .item-tech:hover .status-tech {
        opacity: 1;
    }
    .pict {
        box-shadow: 0px 0px 43px -9px rgba(255, 219, 112, 0.44);

    }
</style>
