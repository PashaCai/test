、import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Tabs, TabsContent, TabsList, TabsTrigger } from "@/components/ui/tabs";
import { Carousel, CarouselContent, CarouselItem } from "@/components/ui/carousel";

export default function CourseOverview() {
  return (
    <div className="p-6 space-y-6">
      <h1 className="text-3xl font-bold">课程总览：手机摄影 & 艺术策展</h1>
      <Tabs defaultValue="photography" className="w-full">
        <TabsList>
          <TabsTrigger value="photography">手机摄影方向</TabsTrigger>
          <TabsTrigger value="curation">艺术策展方向</TabsTrigger>
        </TabsList>

        <TabsContent value="photography">
          <Carousel className="w-full">
            <CarouselContent>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">教学目标</h2>
                    <p>引导学生掌握摄影构图与光影表达，培养日常观察力与主题表达能力，完成一套个人摄影系列作品。</p>
                  </CardContent>
                </Card>
              </CarouselItem>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">课程结构</h2>
                    <ul className="list-disc pl-5 space-y-1">
                      <li>第1周：构图基础 & 光影感知</li>
                      <li>第2周：叙事表达 & 实验性摄影</li>
                      <li>每节课40分钟，共12节</li>
                    </ul>
                  </CardContent>
                </Card>
              </CarouselItem>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">课程进度表</h2>
                    <ul className="list-disc pl-5 space-y-1">
                      <li>第1节：手机摄影的可能性（理论）</li>
                      <li>第2节：走出教室观察拍摄（实践）</li>
                      <li>第11节：拼贴与叠加摄影实验（实践）</li>
                      <li>第12节：作品整理与展示（讲评）</li>
                    </ul>
                  </CardContent>
                </Card>
              </CarouselItem>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">成果展示样式</h2>
                    <p>输出摄影集（6–8张）+ 创作说明，可装订成 Zine 或打印为展板式呈现，用于升学作品集。</p>
                  </CardContent>
                </Card>
              </CarouselItem>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">学生能力发展价值</h2>
                    <div className="grid grid-cols-2 gap-4">
                      <div>
                        <h3 className="font-semibold">手机摄影方向</h3>
                        <ul className="list-disc pl-5 text-sm space-y-1">
                          <li><strong>能力培养：</strong>图像观察力、构图、叙事表达</li>
                          <li><strong>作品集价值：</strong>可转化为“主题摄影系列”展示</li>
                          <li><strong>升学优势：</strong>展现个人风格与艺术思维</li>
                          <li><strong>跨领域能力：</strong>融合摄影、写作、拼贴等表达</li>
                        </ul>
                      </div>
                      <div>
                        <h3 className="font-semibold">艺术策展方向</h3>
                        <ul className="list-disc pl-5 text-sm space-y-1">
                          <li><strong>能力培养：</strong>策展逻辑、图形系统、空间理解</li>
                          <li><strong>作品集价值：</strong>可转化为策展视觉提案展示</li>
                          <li><strong>升学优势：</strong>展现项目型思维与组织力</li>
                          <li><strong>跨领域能力：</strong>融合平面设计、叙事与构成规划</li>
                        </ul>
                      </div>
                    </div>
                  </CardContent>
                </Card>
              </CarouselItem>
            </CarouselContent>
          </Carousel>
        </TabsContent>

        <TabsContent value="curation">
          <Carousel className="w-full">
            <CarouselContent>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">教学目标</h2>
                    <p>培养学生策划能力与展览表达意识，理解展览逻辑与图形系统构建，完成一份策展提案设计。</p>
                  </CardContent>
                </Card>
              </CarouselItem>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">课程结构</h2>
                    <ul className="list-disc pl-5 space-y-1">
                      <li>第1周：策展概念 & 视觉语言</li>
                      <li>第2周：展览系统设计 & 空间模拟</li>
                      <li>每节课40分钟，共12节</li>
                    </ul>
                  </CardContent>
                </Card>
              </CarouselItem>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">课程进度表</h2>
                    <ul className="list-disc pl-5 space-y-1">
                      <li>第1节：什么是策展（理论）</li>
                      <li>第2节：关键词与Moodboard制作（实践）</li>
                      <li>第10节：展览邀请函与导视系统设计</li>
                      <li>第12节：策展成果路演与总结</li>
                    </ul>
                  </CardContent>
                </Card>
              </CarouselItem>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">成果展示样式</h2>
                    <p>输出策展视觉提案，包含主视觉、导视图、空间草图与展览图录页面，可用于升学设计作品集。</p>
                  </CardContent>
                </Card>
              </CarouselItem>
              <CarouselItem>
                <Card>
                  <CardContent className="p-4">
                    <h2 className="text-xl font-semibold mb-2">学生能力发展价值</h2>
                    <div className="grid grid-cols-2 gap-4">
                      <div>
                        <h3 className="font-semibold">手机摄影方向</h3>
                        <ul className="list-disc pl-5 text-sm space-y-1">
                          <li><strong>能力培养：</strong>图像观察力、构图、叙事表达</li>
                          <li><strong>作品集价值：</strong>可转化为“主题摄影系列”展示</li>
                          <li><strong>升学优势：</strong>展现个人风格与艺术思维</li>
                          <li><strong>跨领域能力：</strong>融合摄影、写作、拼贴等表达</li>
                        </ul>
                      </div>
                      <div>
                        <h3 className="font-semibold">艺术策展方向</h3>
                        <ul className="list-disc pl-5 text-sm space-y-1">
                          <li><strong>能力培养：</strong>策展逻辑、图形系统、空间理解</li>
                          <li><strong>作品集价值：</strong>可转化为策展视觉提案展示</li>
                          <li><strong>升学优势：</strong>展现项目型思维与组织力</li>
                          <li><strong>跨领域能力：</strong>融合平面设计、叙事与构成规划</li>
                        </ul>
                      </div>
                    </div>
                  </CardContent>
                </Card>
              </CarouselItem>
            </CarouselContent>
          </Carousel>
        </TabsContent>
      </Tabs>
    </div>
  );
}
