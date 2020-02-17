controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-activation-fn: ['relu', 'relu', 'None']
gating-index: None
dsr-gait-freq: 1.667
render-eval: False
expert-num: 4
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
max-episode-num: 5000000
replay-start-size: 10000
tau: 0.001
epoch-num: 500
max-test-time: 10
dsr-gait-period: 0.6
LLC-frequency: 500
actor-weight-decay: 1e-06
Physics-frequency: 1000
filter-action: True
bullet-default-PD: False
squash-action: True
critic-lr: 0.0003
replay-buffer-size: 1000000
HLC-frequency: 25
rollout-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-layer-size: [32, 32]
task-weight: 0.5
test-num: 4
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
gamma: 0.955
loss-output-smooth-coeff: 2.0
critic-l2-reg: 0.0003
n-step: 1
critic-weight-decay: 1e-06
max-path-num: 20
filter-torque: False
prioritized-exp-replay: True
joint-interpolation: True
action-dim: 12
interpolation: False
actor-layer-size: [256, 256]
max-step-num: 2500000000
loss-entropy-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-ratio: 1
record-start-size: 10000.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: None
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
epoch-step-num: 5000000
max-train-time: 10
state-dim: 25
imitation-weight: 0.5
actor-l2-reg: 0.0003
actor-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
total-step-num: 2500000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-bound-coeff: 0.0
critic-layer-size: [256, 256]
batch-size: 128
