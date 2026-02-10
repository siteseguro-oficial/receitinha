import SiteHeader from "@/components/SiteHeader";
import HeroSection from "@/components/HeroSection";
import WeightCalculator from "@/components/WeightCalculator";
import ProblemSection from "@/components/ProblemSection";
import TransformationSection from "@/components/TransformationSection";
import BenefitsSection from "@/components/BenefitsSection";
import RecipePreview from "@/components/RecipePreview";
import TestimonialsSection from "@/components/TestimonialsSection";
import PricingSection from "@/components/PricingSection";
import GuaranteeSection from "@/components/GuaranteeSection";
import FaqSection from "@/components/FaqSection";
import FinalCtaSection from "@/components/FinalCtaSection";
import StickyCtaBar from "@/components/StickyCtaBar";
import SiteFooter from "@/components/SiteFooter";

const Index = () => {
  return (
    <div className="min-h-screen bg-background">
      <SiteHeader />
      <main>
        <HeroSection />
        <WeightCalculator />
        <ProblemSection />
        <TransformationSection />
        <BenefitsSection />
        <RecipePreview />
        <TestimonialsSection />
        <PricingSection />
        <GuaranteeSection />
        <FaqSection />
        <FinalCtaSection />
      </main>
      <SiteFooter />
      <StickyCtaBar />
    </div>
  );
};

export default Index;
