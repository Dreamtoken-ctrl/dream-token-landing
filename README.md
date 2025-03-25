# dream-token-landing
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { Sparkles, Rocket, Globe2 } from "lucide-react";

export default function DreamLanding() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-950 to-blue-800 text-white flex flex-col items-center justify-center px-6 py-10">
      <div className="text-center max-w-2xl">
        <h1 className="text-4xl md:text-6xl font-bold mb-4">Dream Token (DRM)</h1>
        <p className="text-lg md:text-xl mb-6 text-blue-200">
          Будущее начинается с мечты. Dream — это токен, вдохновляющий на децентрализованные инновации и свободу.
        </p>
        <div className="flex justify-center gap-4 mb-8">
          <Button className="bg-white text-blue-900 font-semibold px-6 py-3 rounded-2xl shadow-md">
            Купить на Uniswap
          </Button>
          <Button variant="outline" className="border-white text-white px-6 py-3 rounded-2xl">
            Смотреть контракт
          </Button>
        </div>
      </div>

      <div className="grid grid-cols-1 md:grid-cols-3 gap-6 mt-10 max-w-5xl">
        <Card className="bg-blue-900/60 border-none">
          <CardContent className="p-6 text-center">
            <Sparkles className="mx-auto h-10 w-10 mb-3 text-blue-300" />
            <h3 className="text-xl font-semibold mb-2">Мечта — это бренд</h3>
            <p className="text-blue-200 text-sm">
              Уникальный токен с креативной айдентикой и запоминающимся логотипом. DRM создан вдохновлять.
            </p>
          </CardContent>
        </Card>

        <Card className="bg-blue-900/60 border-none">
          <CardContent className="p-6 text-center">
            <Rocket className="mx-auto h-10 w-10 mb-3 text-blue-300" />
            <h3 className="text-xl font-semibold mb-2">Стартовая ликвидность</h3>
            <p className="text-blue-200 text-sm">
              DRM уже доступен на Uniswap. Первая ликвидность залита. Готов к росту.
            </p>
          </CardContent>
        </Card>

        <Card className="bg-blue-900/60 border-none">
          <CardContent className="p-6 text-center">
            <Globe2 className="mx-auto h-10 w-10 mb-3 text-blue-300" />
            <h3 className="text-xl font-semibold mb-2">Глобальное видение</h3>
            <p className="text-blue-200 text-sm">
              Цель — вывести Dream в топ токенов. Сообщество, обмен, вдохновение — всё впереди.
            </p>
          </CardContent>
        </Card>
      </div>
    </div>
  );
}

